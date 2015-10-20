Example Metawear Cordova Application
====================================

This is an example application to that guides you through the basic scaffolding of your application,  connecting to your board and finally interacting with it's sensors.  This example has only been tested on Android,  depending on the state of the IOS implementation it may or may not run there.

Steps to Set up your environment:

1. cordova plugin add https://github.com/polyglotprogramminginc/cordova-plugin-metawear
2. cordova platform add android
3. make sure your ANDROID_HOME is pointing to your android sdk.
4. cordova run android

Current functions in the example:

1. Scaffoling
2. Connecting to your board
3. Reading the RSSI value
4. Start Accelerometer
5. Stop Accelerometer
6. Disconnect
