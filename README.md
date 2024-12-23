# React Native FlatList KeyExtractor Error: Non-Unique or Invalid Keys

This repository demonstrates a common error in React Native's `FlatList` component: using non-unique or invalid keys in the `keyExtractor` prop.  This can lead to unexpected behavior, including incorrect rendering, performance issues, and crashes.

## The Problem

The `keyExtractor` prop in `FlatList` is crucial for efficiently updating the list. It requires a function that returns a unique and immutable key for each item in your data array.  If the keys are not unique, React Native will have difficulty identifying which items have changed, resulting in incorrect rendering and potential crashes.

## The Solution

The solution is to ensure that the `keyExtractor` function always returns unique, immutable, and primitive values (strings or numbers) for each item.  Avoid using objects or arrays as keys.

## How to Use This Repository

1. Clone the repository: `git clone <repository_url>`
2. Navigate to the directory: `cd react-native-flatlist-key-error`
3. Run the app (instructions may vary depending on your React Native setup).