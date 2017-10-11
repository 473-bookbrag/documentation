# CPSC 473 Project 1

## Description

This provide provides basic function of web application for Professors to brag about the contents of their bookshelves

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Build With

What things you need to install the software:

* [deployd](http://deployd.com/) - open source platform to build API
* [node.js](https://nodejs.org/en/download/) - an open-source JavaScript run-time environment for executing JavaScript code server-side
* [browser-sync](https://www.browsersync.io/) - browser testing

### Installing

Go to the base directory of your Deployd and create a new project folder:

```
$ dpd create <project>
$ cd <project>
```

## Deployment

```
$ dpd -d
```
if MongoDB is not install in the same directory of your Deployd:
```
$ dpd --mongod "<PATH>MongoDB\Server\3.4\bin\mongod.exe" -d
```



## Acknowledgments
