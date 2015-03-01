# README #

## What is this repository for? ##

**Responsive Menu** is a drop-down menu for responsive websites. It is a **jQuery plugin** that includes a JavaScipt file and CSS file as well as sample HTML.

* **Description**: Drop-down Menu for responsive layouts
* **Requires**: jQuery
* **Author**: John Bowyer-Smyth
* **Copyright**: Copyright 2015 John Bowyer-Smyth
* **License**: MIT
* **Version: 0.1.1**

## How do I get set up? ##

### Summary of set up ###

#### Basic Setup ####

* **Download** - Download and extract the Responsive Menu zip files
* **Copy file**s - Copy the responsive-menu.js and responsive-menu.css files to your project
* **Setup Menu HTML** - Open the menu.html sample file and copy and past the menu html into the html files in your project. Or, setup existing menus in your project to work with Responsive Menu (see Configuration).
* **Link to CSS and JavaScript files** - Add link and script references to your HTML files
* **Initialize Responsive Menu** - Activate the plugin using jQuery (see Configuration)

#### Using Bower Package Manager ####

The Responsive Menu repo includes a bower.json file that can be used for managing the installation and updating of Responsive Menu within your projects.

### Configuration ###

#### Suggested HTML ####

	<a class="rm-toggle rm-button rm-nojs" href="#">Menu</a>
    <nav class="rm-nav rm-nojs rm-lighten">
        <ul> ...

#### Theme class options ####

**Options**: rm-lighten, rm-darken.
rm-lighten theme lightens menu item backgrounds and is best used if your design requires a dark menu background color.
rm-darken theme darkens menu item backgrounds and is best used if your design required a light menu background color.
You can set the menu background color to any color to work with the chosen theme.

#### The Toggle Button ####

An optional menu-btn.png file is included. By default, the same image is included in the CSS as a data URI
so the png file is not required unless you would prefer to use the png file instead of the data URI.

#### Dependencies ####
jQuery, Modernizr (optional)

#### How to run tests ####
No testing framework at this time

#### Task Managers ####
Gruntfile.js and package.json files are included if you want to manage tasks using Grunt.
Note: The Grunt file uses configuration information contained in the package.json

#### Deployment instructions ####
The git repo is versioned and includes a Bower configuration file so the repo can be easily included in your project as a dependency.

## Contribution guidelines ##

Contributions are much appreciated and welcomed.

### Who do I talk to? ###

John Bowyer-Smyth