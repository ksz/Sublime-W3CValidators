Sublime-W3CValidators
=====================

## About

forked from dubharmonic/Sublime-W3CValidators

this is Sublime Text 3 support edition.

---

This is a simplified markup validator package for the Sublime Text 3 text editor that uses the W3C validator web service located at [http://validator.w3.org](http://validator.w3.org).

Unlike similar packages, curl is not required! 

##Installation

~~Via the [Sublime Package Manager](http://wbond.net/sublime_packages/package_control):~~

* ~~`Ctrl+Shift+P` or `Cmd+Shift+P` in Linux / Windows / OS X~~
* ~~Type `install`, select `Package Control: Install Package`~~
* ~~Select `W3CValidators`~~

Manually: clone this project into `Sublime Text 3/Packages`

##Usage

Open an HTML or SVG file, and from the Tools menu go to W3C Validators, and then select the type of document you're validating. The results will be displayed in an alert box.

##Design Decisions

Automatic detection of document types has proven unrealiable, therefore only explicit document type validation is supported. Not all document types are supported, because most of them should be depricated in practice.
