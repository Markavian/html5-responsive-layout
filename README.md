HTML5 Responsive Layout
=======================

I couldn't find a responsive template I liked, so I made my own.

* Preview: http://mkv25.net/showcase/responsive/

Features
--------

* Single, Double, Triple, and Quad columns
* Four layout sizes, maxing out at 1000px width
* Switches to single column mode below 768px for mobile
* Templates for fav icons

File Guide
----------

### index.html
This is the example layout used for testing CSS. 
I've made heavy use of custom tags, such as <navigation>, <footer>, <content>, <column>, and <heading>. These have been nested together with a bit of CSS class markup to denote positions.

### base.css
Taken from:
* Skeleton V1.2
* Copyright 2011, Dave Gamache
* www.getskeleton.com
* http://www.opensource.org/licenses/mit-license.php
* 6/20/2012
This file 

### layout.css
This file contains metrics only for layout and positioning, including sizes for double, triple, and quad, and default padding for content.
Avoid editing this file.

### style.css
This is the place to write custom content for the site layout. It should contain all colour, font, and formatting. 
Some colours, fonts, and columns heights have been added as examples.
