# Webpack Training 1

This is an example repo to walk through a simple webpack config.

## Quickstart Instructions

Run `yarn install` to install necessary dependencies.


Scripts mentioned earlier
==========================
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "build": "webpack --config=webpack.config.prod.js",
    "build-dev": "webpack --config=webpack.config.dev.js",
    "start": "webpack-dev-server --config=webpack.config.dev.js --open"
  },


  "dependencies": {
    "@babel/core": "^7.5.5",
    "@babel/preset-env": "^7.5.5",
    "babel-loader": "^8.0.6",
    "clean-webpack-plugin": "^3.0.0",
    "copy-webpack-plugin": "^4.5.2",
    "css-loader": "^3.2.0",
    "html-webpack-plugin": "^3.2.0",
    "style-loader": "^1.0.0",
    "webpack": "^4.39.1",
    "webpack-dev-server": "^3.7.2",
    "webpack-cli": "^4.7.2",
    "express": "^4.16.3",
    "express-favicon": "^2.0.1"
  },

npm install --save-dev html-webpack-inline-source-plugin 
  "html-webpack-inline-source-plugin": "0.0.10",