# All-Father-Starter-Kit-React
Uses Vite combined with iconic capacitor to build web apps, ios apps and android apps. All in one go.


# Installation
All the necessary commands are given in the package.json file in the scripts section.
  - npm run setup

Notice the setup will create both files for android and ios. If you need only one then feel free to edit the scripts section.

If you are using android 
  - npm run openandroid
  - npm run syncandroid

If you are using ios
  - npm run openios
  - npm run syncios

For web
  - npm run vite

For more on the capcitorjs check out there [docs](https://capacitorjs.com/docs).


# More
  - capacitor.config.json
  ```
  {
    "appId": "io.ionic.nameofyourapp",
    "appName": "nameofyourapp",
    "bundledWebRuntime": false,
    "npmClient": "npm",
    "webDir": "build",
    "cordova": {}
  }
  ```
  
  - ionic.config.json
  ```
  {
  "name": "nameofyourapp",
  "integrations": {
    "capacitor": {}
  },
  "type": "react"
  }
  ```
  
  Note: replace nameofyourapp in both files with the name of your app.
