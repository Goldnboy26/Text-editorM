## Progressive Web App (PWA) : Text Editor

![](https://img.shields.io/badge/Created%20by-Eduardo%20Monje%20Vasquez-blue?style=for-the-badge) 

![](https://img.shields.io/badge/npm%20package-express-orange?style=flat-square&logo=npm)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

The application is a web text editor where the user can create notes or code snippets with or without an internet connection and where the user can reliably retrieve them for later use.  The integrated service worker and Cache API's ensure that the application will remain fully functional even without and active internet connection.  This application allows the user to access visited pages even if the application is offline.

[GitHub-Repo](https://github.com/Goldnboy26/text-editorm) 

🚀The application has been deployed to Heroku and the URL of the deployed application is:-
 
[Heroku-livePage](https://text-main19.herokuapp.com/)

## Table of Contents

* [Installation](#installation)
* [References](#references)
* [License](#license)

## Installation

* This text editor require a number of methods and store data to an IndexedDB database to be builded up.

* This application will require the installation of Node.js and various npm packages.

*   Node Package Manager (npm) is a software manager and installer which puts the modules in place so that the node project can utilize it, and also, it manages dependency conflicts intelligently and initialized using **npm init**. The package.json will be generated and will contains all the details of the application in which the user have inputted during the npm initialization. 

*  This application will use the following npm packages:-

         * npm install express (express.js)
         * npm install --save-dev webpack (Webpack)
         * npm install webpack-dev-server --save-dev (webpack-dev-server)
         * npm install --save-dev webpack-pwa-manifest (WebpackPwaManifest)
         * npm install babel (Babel)
         * npm install --save-dev css-loader (CSS-loader)
         * npm install concurrently --save (run multiple commands concurrently.) (Concurrently)
         * npm npm install idb (IndexedDB)

* The required modules are bundled in the package.json file and at CLI or integrated terminal type in **npm run install**, the modules will be installed.       

``````
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
``````



## References

*   The Unit Ahead : Progressive Web Applications (PWA)
*   Module 19 Mini-Project: Deploy Contact Directory App on Heroku with Script
*   Request-Response : The Full-Stack Blog : Heroku Deployment Guide
 
## License

This project is licensed under the terms of the MIT license.

##QUESTIONS OR CONSERNS

* [GITHUB](https://github.com/Goldnboy26/text-editorm)
* [EMAIL](enrique.monje1994@yahoo.com)