# grunt-sass-starter
A super simple Grunt with Sass starter example with JSHint, livereload and Source Maps ready to roll

## Requirements ##
1. Install [Node.js](https://nodejs.org/en/) on your computer
2. Install Grunt in command line via `npm install -g grunt-cli`
3. Install [Sass](http://sass-lang.com/install)

## Installation
1. Copy and paste both the **package.json** and **Gruntfile.js** into your project directory
2. In command line navigate to your **project directory** and run npm install`
3. Add `<script src="http://localhost:35729/livereload.js"></script>` to your base index.html to allow Livereload to work
4. Run `grunt watch`
5. Start adding code to **app.scss**

### File structure

To link up in your html

CSS File    => /assets/build/app.min.css
JS File     => /assets/build/app.min.js

To work from

SASS        => /assets/sass/
JS          => /assets/js/app.js

^ You can add more JS files to concatenate in your Gruntfile.