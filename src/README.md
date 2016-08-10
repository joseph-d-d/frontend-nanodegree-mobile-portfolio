## Website Performance Optimization portfolio project

### Getting started

####Part 1: Running
* For the Page Speed test [click](https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fjoseph-d-d.github.io%2Ffrontend-nanodegree-mobile-portfolio&tab=desktop) or copy and past https://joseph-d-d.github.io/frontend-nanodegree-mobile-portfolio into PageSpeed Insights.
* For the Pizza webpage Run `index.html` in the dist folder to see the main website and then click on "Cam's Pizzeria" link.

####Part 2: Optimizations For Page Speed On index.html
* Compressed the images and reduced their sizes.
* Moved javascript to a external async file.
* Inlined css. And removed render blocking call to google fonts.
* Minified HTML, CSS and Javascript.
* Added media print to the print CSS.

####Part 3: Optimizations For Pizza On main.js
* Moved as many calculations and selections outside the for loops as possible.
* Used getElementById and getElementByClass instead of queryAll for most large searches.

