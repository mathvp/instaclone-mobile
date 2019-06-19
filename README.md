# instaclone-mobile
This is from a React Native tutorial from Rocketseat OmniStack course
It depends on a Backend (here [NodeJs Backend](https://github.com/mathvp/instaclone-backend)) to receive data via API (with Axios) and show it to the user.
Socket.io was used to simulate a real time experience, so, when the Like button is pressed, the counter is incremented at the same time 'live'.

## How to run
Before run this project you need to setup your [React Native Environment](https://docs.rocketseat.dev/ambiente-react-native/introducao)

After setup, run:  
`react-native run-android`

## Generate apk for Android
To generate an .apk for android you need to follow this steps: https://facebook.github.io/react-native/docs/signed-apk-android  
and after that, run:
`./gradlew assembleRelease`
