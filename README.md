# cssGrid

Kinda tired messing around with overcomplex CSS frameworks? Need some easy to adapt 12 column responsive CSS Grid with breakpoints, some helper classes and CSS Variables? Here you go.

---

## Main Classes

**.grid** enables the grid

**.row** creates a new row

**.col-x** creates a column spanning x columns (1-12)

## Helper Classes

**.xs-hide** hides a column or row on mobile (600px and down)

**.md-hide** hide a column or row on medium devices (600px to 768px)

**.lg-hide** hide a column or row on desktop devices (768px and up)

## Breakpoints

**col-xs-\***: mobile (600px and down)

**col-md-\***: medium devices (600px to 768px)

**col-\***: desktop devices (768px and up)

## Variables

**--grid-col-gap: 6px;** sets the column gap

**--grid-row-gap: 6px;** sets the row gap

**--grid-max-width: 1200px;** sets the max-width of the grid (100% for none)

**--grid-margin: auto;** centers the grid, none for no centering.

---

## How to use?

Include grid.css in your project, add or remove breakpoints, set variables, done.
