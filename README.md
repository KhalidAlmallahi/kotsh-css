# Kotsh - Very simple CSS Framework

Kotsh is a collection of basic components, you will need in every web project to develop responsive & modern interfaces and websites.

* __Website__ http://www.abukotsh.me
* __Documentation__ http://www.abukotsh.me/#/docs
* __Demo__ http://demo.abukotsh.me

## How to use

### Install with Bower
```
bower install kotsh-css
```
Then include CSS and JS files like this:
```
<link rel="stylesheet" href="bower_components/kotsh-css/dist/css/kotsh.min.css">

<script src="bower_components/kotsh-css/dist/js/kotsh.js"></script>
```

## Development
You'll need:
* [git](https://git-scm.com/)
* [npm](https://www.npmjs.com/get-npm)

First clone this repository using [git](https://git-scm.com/):
```
git clone 
```
Now you'll have to install all needed [npm](https://www.npmjs.com/get-npm) dependencies:
```
npm install
```
After that you could use the following commands:
```
// Load & compile all icons to an icon font from ./src/icons/*.svg to ./dist/fonts/*
npm run icons

// Compile all .scss files to ./dist/css/kotsh.min.css
npm run css

// Compile all grid related .scss files to ./dist/css/kotsh.grid.min.css
npm run css-grid

// Watch all .scss files and recompile ./dist/css/kotsh.min.css & ./dist/css/kotsh.grid.min.css if they changed
npm run watch-css
```
