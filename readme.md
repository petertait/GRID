# GRID
#### Simple sass grid – built using the minimal amount of thought.

GRID is made up of columns contained within a single wrapper. There is a built in mobile grid which can target smaller screens to help provide targeted grid structures for all screen sizes.

## Get started

Add the scss file into your sass structure. Customise the amount of columns with the $columns variable.

Wrap your columns within a `.grid` container.

In the example below, `.col--1` equals to 25% width within a 4 column grid structure.


```html
<section class="grid">
  <div class="col col--1 col__mob--4">

  </div>
  <div class="col col--2 col__mob--1">

  </div>
  <div class="col col--1 col__mob--3">

  </div>
</section>
```
