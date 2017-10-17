# Book Bragger!

## Description

This provide provides basic function of web application for Professors to brag about the contents of their bookshelves

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Build With

What things you need to install the software:

* [deployd](http://deployd.com/) - open source platform to build API
* [node.js](https://nodejs.org/en/download/) - an open-source JavaScript run-time environment for executing JavaScript code server-side

### Installing

Go to the base directory of your Deployd and create a new project folder:

```
$ git clone git@github.com:473-bookbrag/deployd-app
$ cd deployd-app
$ npm install
```

Import all files into <project> directory and replace all

## Deployment

```
$ dpd -d
```
if MongoDB is not install in the same directory of your Deployd:
```
$ dpd --mongod "<PATH>MongoDB\Server\3.4\bin\mongod.exe" -d
```
once loaded the browser will open up a page with link: http://localhost:2403/dashboard/ 

the data store in deployd can be found here
<br>
<img height="400" src="https://github.com/473-bookbrag/documentation/blob/master/documentation/Screen%20Shot%202017-10-16%20at%206.19.12%20PM.png">
<br>
click the "open" label on the top right corner
<br>
<img height="40" src="https://github.com/473-bookbrag/documentation/blob/master/documentation/Open.JPG">
<br>
the browser will open up a new page that look like this
<br>
<img height="250" src="https://github.com/473-bookbrag/documentation/blob/master/documentation/Screen%20Shot%202017-10-16%20at%206.17.30%20PM.png">
<br>
when you click on "Login" on the up right corner, it will take you to a new page
<br>
<img height="180" src="https://github.com/473-bookbrag/documentation/blob/master/documentation/Login.JPG">
<br>
when you finish login, the page will be like this (notice your name at the up right corner)
<br>
<img height="250" src="https://github.com/473-bookbrag/documentation/blob/master/documentation/Screen%20Shot%202017-10-16%20at%206.18.39%20PM.png">
<br>
when click on "Post a Bookshelf", a pop-up will be shown like this
<br>
<img height="300" src="https://github.com/473-bookbrag/documentation/blob/master/documentation/PostShelf.JPG">
<br>
same with "Post a book" (bookshelf needed in order to post a book)
<br>
<img height="400" src="https://github.com/473-bookbrag/documentation/blob/master/documentation/PostBook.JPG">
<br>


## Authors

* [DanielSollis](https://github.com/DanielSollis) - Daniel Sollis
* [jasonhan0426](https://github.com/jasonhan0426) - Jason Han
* [Kazander95](https://github.com/Kazander95) - Kazander Antonio
* [philipchungtech](https://github.com/philipchungtech) - Philip Chung
* [shelleypham](https://github.com/shelleypham) - Shelley Pham

## Acknowledgments

* [dpd-fileupload](https://www.npmjs.com/package/dpd-fileupload)
* [fancybox](https://github.com/fancyapps/fancybox)
