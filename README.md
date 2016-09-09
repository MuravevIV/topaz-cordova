# Cordova android application

## Prerequisites

* Java JDK 1.8.0

  * set JAVA_HOME
  * append PATH
 
* Android SDK

  * set ANDROID_HOME
  * append PATH
  * install "Tools/Android SDK Tools"
  * install "Tools/Android SDK Platform-tools"
  * install "Tools/Android SDK Build-tools"
  * install "Android 6.0 (API 23)" (all packages)
  * install "Extras/Android Support Repository" (???)
  * install "Extras/Google Repository" (???)
  * install "Extras/Google USB Driver"

* Gradle (???)

  * append PATH

* Node Package Manager

  * append PATH
 
* Apache Cordova

 ```
 npm install -g cordova
 ```

## Cordova create project

If you don't use this project template, you can create cordova application by executing  this command in empty directory:

```
cordova create .
```

## Cordova initialization

```
cordova platform add android
cordova build
```

## Cordova run

 * [enable USB debugging mode on your android device](https://www.kingoapp.com/root-tutorials/how-to-enable-usb-debugging-mode-on-android.htm)
 * connect your device to PC as multimedia device

```
cordova run
```

"device is ready" message should be present on opened application's view

## Debug in-browser

 * [chrome://inspect/#devices](chrome://inspect/#devices)