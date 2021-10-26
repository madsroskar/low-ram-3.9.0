# Repro to test an example chat app on android with 3GB RAM

## Versions:

* stream-chat-react-native-core@3.9.0
* stream-chat-react-native@3.9.0
* stream-chat@~3.13.1

## To run this app:

1. Install dependencies (`yarn install`)
2. Update `YOUR_API_KEY`, `YOUR_USER_ID` and `YOUR_USER_TOKEN` in [App.tsx](./App.tsx)
3. Run the metro bundler (`yarn start &` or `yarn start` in a separate window)
4. Build the iOS app (`yarn android` or `npx react-native run-android`)
