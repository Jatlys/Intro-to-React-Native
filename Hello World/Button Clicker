import { Text, View, StyleSheet, Button } from 'react-native';
import { useState } from 'react';
export default function App() {
  const [count, setCount] = useState(0);

  function buttonPressed() {
    console.log('Button Pressed');
    setCount(count + 1);
  }

  function renderEncouragingText() {
    if (count >= 10) {
      return 'Keep Going!';
    }
    return null;
  }

  return (
    <View style={styles.container}>
      <Text> {count} </Text>
      <Button title="Press me!" onPress={buttonPressed}></Button>
      <Text style={styles.encouragingText}>{renderEncouragingText()} </Text>
    </View>
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    justifyContent: 'center',
    alignItems: 'center',
  },

  encouragingText: {
    paddingTop: 20,
    color: '#666',
  },
});
