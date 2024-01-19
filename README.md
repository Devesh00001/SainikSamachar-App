# FlatMatePG
if asset not present = mkdir android/app/src/main/assets
if changes happen = react-native bundle --platform android --dev false --entry-file index.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res
build android command = react-native run-android
For releasing unssigned apk = cd android && ./gradlew app:assembleRelease

node version = v16.16.0

    "@react-native-firebase/app": "^18.6.1",


    // "react-native-orientation": "^3.1.3",
    "@react-native-community/netinfo": "^11.2.1",

