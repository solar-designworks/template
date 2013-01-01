Profound Grid
==================

A responsive grid system for fixed and fluid layouts. Built in SCSS/Compass.

### Basic Usage

Pretty much everything in this repo is one big example. The grid is just one file: /sass/grid/_grid.scss

```sass
// //////////////////////
// CONFIG
// //////////////////////

@import 'grid/grid';"

$total_width: 100%;
$container_margin: 3.85%;
$gutter_width: 3.85%;
$max_width: 1233px;

.somecontainer{
	@include container();
}

.somecolumn{
	@include column(9);
}

.somesidebar{
	@include column(3);
	@include push(9);
}
```

### Credits
Credits/Inspiration:
 * -------------------
 * [Semantic Grid](http://www.semantic.gs) Semantic Grid
 * [Susy](http://susy.oddbird.net) Amazing Fluid Grids
 * [Negative Grid](http://chrisplaneta.com/freebies/negativegrid-fluid-css-grid-by-chris-planeta/) Negative Margins