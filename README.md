##Framework.css

###Install

Installing this Platform tool is very simple. All you have to do is download Framework.css or Framework.scss (SASS) in order to get started. 

###Getting Started
####Installing Framework.css

1. Download Framework.css (it already has Normalize.css prepackaged with it)
2. Include `<link href="framework.css" rel="stylesheet" />` in the `<head>` section of your App
3. Start using it!

####Enable responsiveness

To enable responsive functionality, simply add 
``` HTML
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
```
in the `<head>` section of your App, after your stylesheet.

####Creating a layout

Using the built-in grid system of Framework.css is easy. To create rows, add the `.row` class to an element you are targeting. By default, these rows have a `max-width` of 1200px. Within rows, you can create columns, in order to achieve a more complex layout. Add the class ".column" followed by a size class (example: ".third"), and you'll have a grid!

``` HTML

<div class="row">
   <div class="column third">
       Hello there, I'm in a third!
   </div>
   <div class="column third">
       Hello there, I'm in a third!
   </div>
   <div class="column third">
       Hello there, I'm in a third!
   </div>
</div>
``` 

Full list of column sizes:

- .full
- .three-fourths
- .two-thirds
- .half
- .third
- .fourth

###Getting Started with SASS

First, make you sure you have SASS installed on your machine. If you don't, go here to get started with SASS. 
