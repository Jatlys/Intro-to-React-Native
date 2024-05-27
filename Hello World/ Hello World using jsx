import * as React from 'react';
import { Text, View, StyleSheet, Image } from 'react-native';

const localImage = require('./cat.jpg');

export default function App() {
  return (
    <View style={styles.container}>
      <View style={styles.fillerContainer}></View>
      <View style={styles.titleContainer}>
        <View style={styles.imageRow}>
          <Image
            source={{
              uri: 'https://media.giphy.com/media/nn8uzAnxuchf2OWXNy/giphy.gif?cid=ecf05e476b2gw3vph1f8l7z7jwv4udoziswrfw57yhg1osil&ep=v1_gifs_search&rid=giphy.gif&ct=g',
            }}
            style={styles.image}
          />
          <Image 
          source={localImage} 
          style={styles.image} />

        </View>
        <Text style={[styles.header, styles.fontSizeLarge]}> Jatlyson </Text>
        <Text style={styles.subheader}>SUTD Class of 2027</Text>
      </View>
      <View style={styles.fillerContainer}></View>
    </View>
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    justifyContent: 'center',
    alignItems: 'center',
    backgroundColor: 'black',
  },
  header: {
    color: 'red',
    fontWeight: 'bold',
  },
  fontSizeLarge: {
    fontSize: 60,
  },
  subheader: {
    color: 'white',
    textAlign: 'center',
    marginVertical: 10,
  },
  fillerContainer: {
    flex: 1,
    height: 50,
    width: '40%',
    backgroundColor: 'yellow',
  },
  titleContainer: {
    backgroundColor: 'purple',
    padding: 20,
    borderRadius: 20,
    justifyContent: 'center',
    alignItems: 'center',
    width: '100%',
    height: '35%',
  },
  imageRow: {
    flexDirection: 'row',
    justifyContent: 'center',
    width: '50%',
    height: '50%',
  },
  image: {
    height: '100%',
    width: '50%',
    marginHorizontal: 5,
    borderRadius: 50, 
  },
});
