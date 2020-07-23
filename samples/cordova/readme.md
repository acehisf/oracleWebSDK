# Cordova Hybrid App

Use the ODA Web SDK in a Cordova to add skill/DA to your hybrid app.

## Requirements

* This sample requires [NodeJS](https://nodejs.org/) to install dependencies. It is compatible with latest versions of nodeJS.

* This sample requires [Apache Cordova](https://cordova.apache.org/#getstarted) to be installed in your system.
```sh
$ npm install -g cordova
```

* To build Android and iOS apps, you need to have Android Studio and Xcode installed respectively.

## Installation

At the root of the folder, run the command below to install dependencies and cordova plugins.
```sh
npm install --no-optional
```

After this, install the platforms you want to build the app for:
```sh
cordova platform add android
cordova platform add ios
cordova platform add browser
```

Once the platforms are added, check the requirements to see any additional installations or steps are needed to be performed.
```sh
cordova requirements
```

## Run

Once the requirements are met, you can build and run the apps.

### Android

```sh
cordova run android
```

### Web

```
cordova run browser
```

### iOS

```
cordova run ios
```

The above command will run the app in your emulator if no device is connected to your machine.

If you want to test the app on an iPhone or an iPad, you will need to use Xcode. Open `./platforms/ios` in Xcode and build from there. You will need to provide a signature to run your app on the physical devices.
