# plugins-test

Sample app demonstrating [Apache Cordova](https://cordova.apache.org) (also known as [Adobe PhoneGap](http://phonegap.com)) plugins usage in an [AngularJS](http://angularjs.org) context...

The application is also based on the [Ionic Framework](http://ionicframework.com).

## Quick start

+ Ionic npm module needs to be installed on your local machine
>
``` bash
$ npm install -g ionic 
```

+ In the app folder, type:
>
``` bash

$ ionic platform remove android

$ ionic platform add android

$ cordova plugin add org.apache.cordova.console
$ cordova plugin add org.apache.cordova.device
$ cordova plugin add org.apache.cordova.device-motion
$ cordova plugin add org.apache.cordova.inappbrowser
$ cordova plugin add org.apache.cordova.statusbar
$ cordova plugin add org.apache.cordova.vibration
$ cordova plugin add org.apache.cordova.geolocation
$ cordova plugin add org.apache.cordova.network-information
```

+ To play with the application on Android simulator, type:
>
``` bash
ionic emulate android
```

+ To play with the application on your favorite Android device, type
>
``` bash
ionic run android
```

## Copyright and license

    This was heavily influenced by The Enlightened Developer. Go check his stuff out.


