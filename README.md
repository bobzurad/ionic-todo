This project is a todo mobile app for iOS and Android built using the [Ionic Framework](http://ionicframework.com/)

All of the initial code came from the [Ionic Guide](http://ionicframework.com/docs/guide/)

Ionic also has a great [getting started guide](http://ionicframework.com/getting-started/) which I recommend checking out.

###Installation
To get this project up and running:
* Install [node.js](http://nodejs.org/)
* Follow the steps in Cordova's [Android Platform Guide](http://cordova.apache.org/docs/en/5.0.0/guide_platforms_android_index.md.html#Android%20Platform%20Guide)
  * You do not need to install the Cordova Shell Tools
  * Stop at step "Create a New Project"
* Follow the steps in Cordova's [iOS Platform Guide](http://cordova.apache.org/docs/en/5.0.0/guide_platforms_ios_index.md.html#iOS%20Platform%20Guide)
  * Stop at step "Create a New Project"
* Install Cordova and Ionic by running the following command:
  * npm install -g cordova ionic
* Clone this repository

Before you can run this project, you must add the iOS and Android platforms to the project. The platform files are not to be checked in to source control (as specified in the .gitignore file). To add the platform files, cd into the project folder and run:
```bash
$ ionic platform add ios
$ ionic platform add android
```

You can then build the project
```bash
$ ionic build ios
$ ionic build android
```

And run the project in an emulator
```bash
$ ionic emulate ios
$ ionic emulate android
```

For more info on Ionic, check out the [getting started guide](http://ionicframework.com/getting-started/) and the [docs](http://ionicframework.com/docs/)
