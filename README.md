# Materialize + Gulp Boilerplate
[![devDependency Status badge](https://david-dm.org/Dogfalo/materialize/dev-status.svg)](https://david-dm.org/Dogfalo/materialize#info=devDependencies)


[Materialize](http://materializecss.com/), a CSS Framework based on material design. Uses SASS, and has many JS components.

[Gulp](https://github.com/gulpjs/gulp) is a toolkit for automating painful or time-consuming tasks in your development workflow, so you can stop messing around and build something.

#### Supported Browsers:
Chrome 35+, Firefox 31+, Safari 7+, IE 10+

#### Dependencies
Make sure you have [NPM](https://docs.npmjs.com/getting-started/installing-node) and [Node](https://docs.npmjs.com/getting-started/installing-node) installed before getting started.

#### Quickstart:

###### 1. Clone materialize_gulp repo
```shell
$ git clone git@github.com:jsthack/materialize_gulp.git
```
###### 2. Change into materialize_gulp directory
```shell
$ cd materialize_gulp
```
###### 3. Install gulp locally in your project
```shell
$ npm install --save-dev gulp
```
###### 4. Install Gulp-Sass locally + save as dev dependancy
```shell
$ npm install --save-dev gulp-sass
```
###### 5. Install Gulp-Livereload locally + save as dev dependancy
```shell
$ npm install --save-dev gulp-livereload
```

##### 6. Then Open the package.json file and edit to your needs

---

#### Folder Structure

```
materialize_gulp/
|---css/
|   |---materialize.css
|   |---main.css
|---fonts/
|---js/
|---sass
|   |---components/
|   |---materialize.scss
|   |---main.scss
|---gulpfile.js
|---package.json
```

### Gulpfile
The gulpfile is configured to do 2 tasks. Watch all the SCSS files for changes, and compile them into CSS on save. Gulp outputs all the compiled framework SCSS into a file called materialize.css. And compiles your styles in main.scss into a file called main.css. It's also configured with Livereload. It watches all the SCSS and HTML files, and on save it will reload your browser.

Configure the Gulpfile to fit your exact needs.

License
---
Copyright (c) 2017 Cosmin Haims // Licensed under the MIT License
