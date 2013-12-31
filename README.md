express-base
============

Express Basic Server with MongoDB



To run with the REST services:

Make sure Node.js and MongoDB are installed on your system

Go to the angular-directory/server folder and run:
npm install

Run:
node server

In app.js, change:

angular.module('myApp', [
    'ngRoute',
    'myApp.controllers',
    'myApp.memoryServices'
]).

to:

angular.module('myApp', [
    'ngRoute',
    'myApp.controllers',
    'myApp.restServices'
]).

To avoid cross-domain issues, access the application from the following URL:

http://localhost:3000