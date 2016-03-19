# Snapspot-Framework
A new, minimal CSS framework built with fast page load times and modularity in mind. A must have framework for any website! This is by no means the fastest CSS framework or the most minimal, but we think that it is a very good medium between minimal and modular.

# Why Snapspot?
There are tons of other CSS frameworks, and I mean **tons**. Most frameworks either have too much content and so people get lost in all of their different modules, or that they are not fast and minimal. Snapspot aims to fix both of those problems.

The goal of Snapspot is to create modularity. The way the framework is used is simple: You must use the `snapspot.core.css` file if you wish to use any other modules, and then you can just add them in as you please. Let's say that you are looking for a nice, easy-to-use responsive grid for your site. Snapspot has a module called `snapspot.grid.css`. Just include this and the core and then you can start using all of the features from the grid module! Snapspot allows you to speed up your website by removing unnecessary style sheets that you don't want or need.

# We use SASS!
Snapspot is built using SASS (SCSS to be specific). Because we upload all of our original `.scss` files to this repository as well, this means that you can customise variables and recompile them into `.css` files with your own values! For example, if you aren't happy with the media query breakpoints that we use then you can just change the values of them! Or say that you want to change the default font. You can just change the variable `google-font` to a font that you like in the Google Web Fonts Library, and then recompile!

_Tip: When customising the `google-font` variable, the value must be the value of the `family` variable from the URL you get from Google for your font. For example, the value you need from the Google Font URL `https://fonts.googleapis.com/css?family=Open+Sans` is `Open+Sans`!_

# Current Speed
Using the Average Load Time Tester chrome extension with Force Refresh Enabled and all Snapspot Modules loaded: `0.095 seconds` for the Load Event to End.

Using the `grid.html` example file.

# Total Framework Size: 1.55KB
