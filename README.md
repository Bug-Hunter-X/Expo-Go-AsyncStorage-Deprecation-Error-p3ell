# Expo Go AsyncStorage Deprecation Error

This repository demonstrates a common error encountered when using AsyncStorage in Expo Go and provides a solution using MMKV.  AsyncStorage is deprecated and will be removed; this example shows how to transition to the recommended alternative.

## Problem

When running an Expo app in Expo Go that uses AsyncStorage, you'll see an error message indicating that AsyncStorage is deprecated and should be replaced with MMKV. This is because AsyncStorage's functionality is being removed in Expo Go.

## Solution

The recommended solution is to migrate your app to use MMKV. This repository provides an example of how to do this.  MMKV offers improved performance and stability compared to AsyncStorage.

## How to reproduce

1. Clone this repository.
2. Install the necessary packages: `expo install mmkv-storage`
3. Run the app in Expo Go.
4. Observe the error message (in `bug.js`).
5. Switch to the corrected version (`bugSolution.js`) to see the solution.