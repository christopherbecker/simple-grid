# simple-grid
A simple grid using flex.

## Install

Add to `head` of HTML.
```<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/christopherbecker/simple-grid@1.0/simple-grid.min.css" />```

## How to use

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

Is a class used to indicate on what breakpooint do you want flex to stack.

### HTML
```
<div class="container br-xs-container">
  <div class="col-5 col-sm-10">
    1
  </div>
  <div class="col-5 col-sm-5">
    2
  </div>
</div>
```
