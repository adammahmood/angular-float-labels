angular-float-labels
=====================

AngularJS implementation of [float labels](http://bradfrostweb.com/blog/post/float-label-pattern/)
Forked from [chrisronline/angular-float-labels](https://github.com/chrisronline/angular-float-labels)

This fork allows you to specify seperate placeholder and label text. This also allows you to target only specific fields to have floating labels (rather than ALL input fields).


Installation
---------
Bower:

    bower install angular-float-labels-extended --save


Usage
---------
**app.js:**

    angular.module('myAwesomeApp', ['angular-float-labels'])
***
**form.html**

    <input type="text" floatlabel="First Name" placeholder="Enter some text"/>
    <input type="email" floatlabel="Email Address" placeholder="Enter your email"/>
***

Customize
-------

Override CSS classes defined within angular-float-labels.css or simply do not include it and create them all yourself.


Example
---------
Please view the [demo](http://www.chrisronline.com/angular-float-labels/index.html)


Release Notes
---------
- v0.0.1 - Basic input support
