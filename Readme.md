## Ionic stuff

This repository has some ionic experiences i made.

#### [Websitetoapk](https://github.com/joaolrc/ionic/Websitetoapk) (Ionic Webview)
 This is a basic webview in ionic which is linked to a website i am making. APK for android is already built in platforms\android\app\build\outputs\apk\debug.
Feel free to use it with your own website as a way to adapt it for mobile users.
Just edit the \src\pages\home\home.ts file with your URL.

After that rebuild the application:

 ```
 ionic cordova build android

 ```
or for ios (iphone):

```
ionic cordova build ios

```
You should have the latest version of ionic installed and gradle, (which you can install with chocolatey) for building for android systems.

Ionic also provides a cool devops app wich can be obtained from the playstore. Install it and run your application from your PC to your mobile with:

```
ionic serve --devapp

```
