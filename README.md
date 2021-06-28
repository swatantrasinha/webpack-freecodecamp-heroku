## Quickstart Instructions
Run `yarn install` to install necessary dependencies.

npm run dev => it will open browser and show the output


Now for production environment check:
npm run postinstall => it will create dist folder and minified files will be there
npm start => it will serve application on port 5000 if local else on production whatever port is there

localhost:5000

=========================
Scripts mentioned earlier
==========================
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "build": "webpack --config=webpack.config.prod.js",
    "build-dev": "webpack --config=webpack.config.dev.js",
    "start": "webpack-dev-server --config=webpack.config.dev.js --open"
  },
