# Pug-Sass Starter

A simple starter for building HTML templates with Pug and Sass.

## Requirements

Make sure [Node JS](https://nodejs.org), [NPM](https://www.npmjs.com) and [Gulp](http://gulpjs.com/) already installed on your computer.

## Install

* Navigate to the directory where the _pug-sass-starter_ folder is located using **Terminal**.
* Execute `npm install`.

## Run

* Execute `npm start` or `gulp`.
* Open `http://localhost:8080/` on your web browser.

## Folder Structures

* **assets**
  * **css** : This folder contains `styles.min.css` (do not edit this file).
  * **fonts** : Store your fonts here, also do not forget to import it on `_variables.scss` (my recommendation).
  * **icons** : Store your icons here.
  * **images** : Store your images here.
  * **js** : This folder contains `scripts.min.css` (do not edit this file).
* **pug**
  * **base**
    * `base.pug` : Base pug file.
    * `header.pug` : Store your header pug code here.
    * `footer.pug` : Store your footer pug code here.
  * **pages**
    * `index.pug` : Example page pug, it contains h1 only.
* **src**
  * **js**
    * `scripts.js` : Store your js code here.
  * **sass**
    * **base**
      * `_global.scss` : Global styles for html, body, section, headings, anchor etc.
      * `_mixins.scss` : Store your mixins here;
      * `_placeholders.scss` : Store your placeholders here;
      * `_variables.scss` : Store your variables here;
    * **components**
      * `_components.scss` : It contains components styles such as buttons, modals etc. If you sparate your components, do not forget to import on it file.
    * **layouts**
      * `_footer.scss` : It contains footer styles.
      * `_header.scss` : It contains header styles.
    * **pages**
      * `_index.scss` : Example sass for specific page (index page).
    * `styles.scss` : Import all scss files.
* `index.html` : Prebuild HTML file, other HTML files will be placed on root folder.

## Gulp Plugins

* [gulp-connect](https://www.npmjs.com/package/gulp-connect) : Run webserver (with livereload).
* [gulp-plumber](https://www.npmjs.com/package/gulp-plumber) : Prevent pipe breaking caused by errors from gulp plugins.
* [gulp-pug](https://www.npmjs.com/package/gulp-pug) : Gulp plugin for compiling Pug templates, compile Pug into HTML.
* [gulp-rename](https://www.npmjs.com/package/gulp-rename) : Gulp plugin to rename files easily, adding `.min` suffix.
* [gulp-sass](https://www.npmjs.com/package/gulp-sass) : Compile your SCSS into CSS.
* [gulp-uglify](https://www.npmjs.com/package/gulp-uglify) : Minify your JS.
