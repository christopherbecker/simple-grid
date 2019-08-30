# Simple-grid
A simple grid using flex.

Simple-grid is straighforward, easy to use and **lightweight**, only **1.5kb** gZipped.

## Install

Add to `head` of HTML.

```<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/christopherbecker/simple-grid@2.5/simple-grid.min.css" />```

## How to use

### HTML

```
<div class="container">
  <div class="col-1">
    1
  </div>
  <div class="col-1">
    2
  </div>
  <div class="col-1">
    3
  </div>
  <div class="col-1">
    4
  </div>
  <div class="col-1">
    5
  </div>
  <div class="col-1">
    6
  </div>
  <div class="col-1">
    7
  </div>
  <div class="col-1">
    8
  </div>
  <div class="col-1">
    9
  </div>
  <div class="col-1">
    10
  </div>
  <div class="col-1">
    11
  </div>
  <div class="col-1">
    12
  </div>
</div>
```

## Responsive

### Breakpoints

* &gt; 1200px
`.col-*`

* 1200px
`.col-lg-*`

* 992px
`.col-md-*`

* 768px
`.col-sm-*`

* 576px
`.col-xs-*`

```
<div class="container">
  <div class="col-4 col-xs-12">
    1
  </div>
  <div class="col-4 col-xs-6">
    2
  </div>
  <div class="col-4 col-xs-6">
    3
  </div>
</div>
```

## Demo

[Simple-grid on JSFiddle](https://jsfiddle.net/cmb86/ut65hmc1/)



# Simple-grid-slider
A simple grid slider using flex that is also mobile compatible. You can use this with the simple-grid shown above.

## Install

Add to `head` of HTML.

```<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/christopherbecker/simple-grid@2.5/simple-grid-slider.min.css" />```

Add to bottom of HTML before the cloing body tag `</body>`.

```<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/christopherbecker/simple-grid@2.5/simple-grid-slider.min.js" />```

## How to use

### HTML

```
<div class="top-container">
  <div class="container simple-grid-slider">
    <div class="col-6 col-xs-12 section">
      1
    </div>
    <div class="col-6 col-xs-12 section">
      2
    </div>
    <div class="col-6 col-xs-12 section">
      3
    </div>
    <div class="col-6 col-xs-12 section">
      4
    </div>
  </div>

  <a href="#" class="left">Left</a>
  <a href="#" class="right">Right</a>
</div>
```

### JS

```
simpleGridSlider('.top-container');
```

## Demo

[Simple-grid-slider on JSFiddle](https://jsfiddle.net/cmb86/bvdt0mrc/)
