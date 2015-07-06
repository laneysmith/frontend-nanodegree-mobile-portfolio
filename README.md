## Website Performance Optimization portfolio project

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

To get started, check out the repository, inspect the code,

### Getting started

####Part 1: Optimize PageSpeed Insights score for index.html

Source code: https://github.com/laneysmith/frontend-nanodegree-mobile-portfolio/

Live site: http://laneysmith.github.io/frontend-nanodegree-mobile-portfolio/

Improved PageSpeed Insights score to 95/100 for mobile & 96/100 for desktop for http://laneysmith.github.io/frontend-nanodegree-mobile-portfolio/index.html

This was accomplished by...
* adding media="print" to the print.css stylesheet, so it only loads when in print view
* inlining critical css (all css) from style.css
* adding async to external JS files
* minifying images using Grunt
* inlining the Google font

####Part 2: Optimize Frames per Second in pizza.html

Source code: https://github.com/laneysmith/frontend-nanodegree-mobile-portfolio/views/

Live site: http://laneysmith.github.io/frontend-nanodegree-mobile-portfolio/views/pizza.html

Optimized http://laneysmith.github.io/frontend-nanodegree-mobile-portfolio/views/pizza.html to comply with 60 fps rule

This was accomplish by...
* where possible, moving variables outside of loops so they're only declared once
* changeing # of pizzas in background from a fixed # to a calculation based on screen height
