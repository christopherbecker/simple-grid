# Simple-grid
A simple grid using flex. This grid uses a 10 column layout.

Simple-grid is straighforward to use and **lightweight**, only **1.4kb**.

## Install

Add to `head` of HTML.

```<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/christopherbecker/simple-grid@1.0/simple-grid.min.css" />```

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
</div>
```

## Responsive

### Breakpoints

* 1200px
* 992px
* 768px
* 576px

```
.br-lg-container
.br-md-container
.br-sm-container
.br-xs-container
```

If you wanted to stack the above html on mobile, simply add `br-xs-container` to the `.container` class.

## Reason

I created this repository, because this Simple-grid is a layout I use on all my projects, and now anyone can use it.
