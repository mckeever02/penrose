**Development is currently taking place in the Version2 branch so clone that one**

# Penrose

A do-with-it-what-you-please starter theme for Wordpress that is built upon the wonderful [Bones theme](https://github.com/eddiemachado/bones) and uses Gulp for assets management.  




## What does it do?

It uses [WPGulp by Ahmad Awais](https://github.com/ahmadawais/WPGulp) to do:

 - Live reload with Browser-Sync
 - Sass to CSS, autoprefixing, sourcemaps, merge media queries, and minify CSS
 - Concatenates and minifies JS files within a Vendor and Custom folder into one js file each
 - Compresses PNG, JPEG, GIF and SVG
 - watch for changes in CSS, JS and php
 - InjectCSS for faster reloading

## Get up and running

 1. Clone the `Version2` Branch to wherever you please on your computer.
 2. Configure your Project Configuration variables in `gulpfile.js`
 3. `cd` into your root folder in terminal and run `npm install`. This will install all of the `node_modules` required by Gulp
 4. Once the `node_modules` have been installed, type `gulp` into your Terminal window and boom. You're up and running.

## How to's

 - Run `gulp images` to optimise all of the images inside of `library/img/raw/` and move them into `library/img/`
 - To build an installable zip file of your theme, use command `gulp build` and your project.zip file will be created as well as a `buildTheme` folder, where you can see what was zipped.
 - Run `gulp styles` to only minify the SASS files



## Dependencies

 - You need to have Node, NPM and Gulp installed globally
