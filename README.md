##Dashing.css

```
Note - This build is a work in progress. It is probably going to change quite a bit until we have put together a full release candidate.
```

###Install

Installing this Platform tool is very simple. All you have to do is download [Dashing.css](https://raw.github.com/samaritanministries/dashing-css/master/dashing.css) or [Dashing.scss (SASS)](https://github.com/samaritanministries/dashing-css/tree/master/sass) in order to get started.

###Getting Started
####Installing Dashing.css

[Download Dashing.css](https://raw.github.com/samaritanministries/dashing-css/master/dashing.css) (it already has [Normalize.css v3.0.1](http://necolas.github.io/normalize.css/) prepackaged with it), then include the following code in the `<head>` section of your App:

``` HTML
<link href="dashing.css" rel="stylesheet" />
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
```
All set! You're ready to rock.

####Creating a layout

Using the built-in grid system of Dashing.css is easy. To create rows, add the `.row` class to an element you are targeting. By default, these rows have a `max-width` of 1200px. Within rows, you can create columns, in order to achieve a more complex layout. Add the class ".column" followed by a size class (example: ".third"), and you'll have a grid!

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

#####...more documentation coming soon.

###Getting Started with SASS

First, make you sure you have SASS installed on your machine. If you don't have it, [go here to get started with SASS](http://sass-lang.com/install).

After SASS is installed, run

``` shell
sass -w sass/dashing.scss:dashing.css --style compressed
```

#####...more documentation coming soon.
