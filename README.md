# React Native useRef Hook and TextInput Value Update Issue

This repository demonstrates a common issue encountered when using the `useRef` hook with TextInput components in React Native. The problem arises when trying to directly access the TextInput's value using `ref.current.value`. This approach often returns outdated or unexpected values.

The provided code illustrates the problematic scenario and demonstrates a robust solution using the `onChangeText` event handler to manage TextInput value updates.