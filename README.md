# React Native TypeError: Cannot read properties of undefined (reading 'property')

This repository demonstrates a common error in React Native applications: the `TypeError: Cannot read properties of undefined (reading 'property')` error. This error occurs when attempting to access a property of an object that is currently undefined or null.  The example showcases this error in the context of fetching asynchronous data. A solution is provided to handle potential null or undefined values.

## How to reproduce
1. Clone this repo.
2. Run `npm install`.
3. Run the app on an emulator or device.
4. Observe the error. 

## Solution
The solution involves using optional chaining (`?.`) or the nullish coalescing operator (`??`) to gracefully handle cases where the object might be undefined or null before the data is fetched.