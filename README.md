# Configuration Webpack 4 with VueJS
## 1. Create a new app (folder)
## 2. Open the folder in your code editor and run terminal
## 3. Initialize our project
`npm init`
## Install Webpack, webpack-cli, webpack-dev-server and path
`npm install webpack webpack-cli webpack-dev-server path --save-dev`
## Editing the "script" object in the package.json file
Delete the string "test". Add the following lines:
```
"scripts": {
  "dev": "webpack-dev-server --open --mode development",
  "build": "webpack --mode production"
},
```
## Create a new file webpack.config.js in root folder
