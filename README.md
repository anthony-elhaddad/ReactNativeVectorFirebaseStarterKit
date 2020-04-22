﻿# ReactNativeVectorFirebaseStarterKit

**Packages**
* react-native-firebase, can be found [here](https://rnfirebase.io/ "Firebase")
* react-native-vector-icons, can be found [here](https://github.com/oblador/react-native-vector-icons "") 
* react-native-paper can be found [here](https://github.com/callstack/react-native-paper "")
* react-navigation v.5 +
* Not using expo

**To get the template up and running**
1. Head over to [Google Console](https://console.firebase.google.com/u/0/ "Google Console") and create a new project.
2. Download the **google-services.json** generated upon registering a new (android) app.
3. Place the **google-services.json** in android/app.
4. `npm install` or `yarn install`
5. `react-native run-android`, and should be up and running.

if there happen to be an error, just `cd android && ./gradlew clean`, then `react-native run-android`
