# All-Father-Starter-Kit-React
Uses Vite+Electron combined with iconic capacitor to build web apps, ios apps, android apps and desktop apps. All in one go.


# Installation
Fork/ clone this repo and you can get started.

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

For desktop
  - npm run desktop-app

Note: If you are using react-router. The BrowserRouter component works well with request based frameworks like react, it may not work at all with file-based environments like Electron. The react-router-dom package ships with the [Hash Router](https://v5.reactrouter.com/web/api/HashRouter) Component that works like a [BrowserRouter](https://v5.reactrouter.com/web/api/BrowserRouter) in a file-based environment


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
  
  For more on the capcitorjs check out there [docs](https://capacitorjs.com/docs).
