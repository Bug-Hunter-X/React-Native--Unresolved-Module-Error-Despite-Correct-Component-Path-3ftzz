# React Native Unresolved Module Error

This repository demonstrates a common yet tricky error in React Native: the 'Unable to resolve module' error, even when the component is correctly placed.

The issue arises from incorrect or missing export statements in the component's module.

## Bug

The `MyComponent.js` file contains the component, but it's missing the necessary `export default` statement. This prevents React Native from properly importing and using it.

## Solution

The `MyComponentFixed.js` file demonstrates the corrected version, with the `export default` statement added to properly export the component.

## Setup:

1. Clone the repo
2. Run `npm install` or `yarn install`
3. Run the project using your preferred React Native method (e.g., `npx react-native run-android`).