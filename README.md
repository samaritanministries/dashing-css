##Framework.css

```
Note - This build is a work in progress. It is probably going to change quite a bit until we have put together a full release candidate. 
```

###Install

Installing this Platform tool is very simple. All you have to do is download [Framework.css](https://raw.github.com/samaritanministries/framework.css/master/framework.css) or [Framework.scss (SASS)](www.github.com) in order to get started. 

###Getting Started
####Installing Framework.css

1. [Download Framework.css](https://raw.github.com/samaritanministries/framework.css/master/framework.css) (it already has [Normalize.css](http://necolas.github.io/normalize.css/) prepackaged with it)
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

- .full (100%)
- .three-fourths (75%)
- .two-thirds (66.6666666%)
- .half (50%)
- .third (33.3333333%)
- .fourth (25%)

####Using utility classes

Sometimes you want to do something simple to an element, but you really don't want to change your stylesheet for it. We've created so easy, no-brainer utility "action classes" for you to use in your App, just to make your life easier. Just add one of these classes to an element, and you'll be good to go.

``` CSS
.hide {
  display: none !important;
}

.fixed {
  position: fixed !important;
}

.relative {
  position: relative !important;
}

.float-left {
  float: left !important;
}

.float-right {
  float: right !important;
}

.float-none {
  float: none !important;
}

.center-text {
  text-align: center !important;
}

.remove-margin {
  margin: 0 !important;
}

.remove-padding {
  padding: 0 !important;
}
```

For example, if you wanted to hide some header text, you would simply add the `.hide` class onto that element, and it will disappear from the page.

``` HTML
<h1 class="hide">Some header text</h1>
```

###Getting Started with SASS

First, make you sure you have SASS installed on your machine. If you don't have it, [go here to get started with SASS](http://sass-lang.com/install).
