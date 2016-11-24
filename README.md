# Project 4 -Udacity Front-End Nonodegree

## Website Performance Optimization portfolio project

### Instructions
To view the portfolio website download all the files and open index.html in your browser.

To view the pizza website download all of the files and open views/pizza.html in your browser.


### Optimizations

#### index.html

* Combined css elements and used inlined css in html pages.
* Replaced Google font with standard font.
* Added media attribute to print.css.


#### main.js and pizza.html

* Modified the code to calculate number of pizza needed to fill webpage based on browser size.
* Cached the required DOM elements.
* Moved the document.body request out of **for** loop in the **changePizzaSizes** and **updatePositions** functions.
* Changed instances of **querySelector** to the more efficient **getElementById** and **getElementByClassName**.

### Peformance

When tested on _PageSpeedInsights_

#### Original Site
**Mobile 28/100**
**Desktop 30/100**

#### Optimized Site
**Mobile 93/100**
**Desktop 92/100**
