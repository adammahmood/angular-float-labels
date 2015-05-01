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

    <!-- Label resolves to "First Name" -->
    <input type="text" floatlabel="First Name" placeholder="Enter some text"/>

    <!-- Label resolves to "Enter your email" -->
    <input type="email" floatlabel="" placeholder="Enter your email"/>

    <!-- Label resolves to "First Name" -->
    <input class="floatlabel: First Name;" type="text" placeholder="Enter some text"/>

    <!-- Label resolves to "Enter your email" -->
    <input class="floatlabel" type="email"  placeholder="Enter your email"/>
***

Customize
-------

Override CSS classes defined within angular-float-labels.css or simply do not include it and create them all yourself.


Example
---------
Please view the [demo](http://www.chrisronline.com/angular-float-labels/index.html)


Release Notes
---------
- v0.1.0 - Supports use of directive via class name or attribute and uses placeholder text if floatlabel text not provided
- v0.0.9 - No longer uses placeholder attribute for label, now uses floatlabel attribute for label text
- v0.0.1 - Basic input support
