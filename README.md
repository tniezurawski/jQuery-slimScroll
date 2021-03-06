# What is slimScroll?

### EDIT CHANGELOG:

Still all credits to Piotr Rochala.

## 09.09.2016
- added animate option for animating scrollTo effect.
- version 1.3.8 released

## 20.05.2016
- added enable/disable option to slimscroll to get control over it. 

### NEW FEATURES USAGE

## Animate scrollTo

1. Add `animate: true` option, like this:
  
  - `$element.slimScroll({ scrollTo: 100, animate: true });`

## Enable/disable Slimscroll

1. save the reference to the object:

  - `var myFirstScroll = $('.elements').slimScroll(options).get(0);`

2. From whatever moment you prefer, please use:

  - `myFirstScroll.enabled = false;` - to stop slimscroll from scrolling
  - `myFirstScroll.enabled = true;` - to let the slimscroll scrolling again


### ORIGINAL README:

slimScroll is a small jQuery plugin that transforms any div into a scrollable area with a nice scrollbar - similar to the one Facebook and Google started using in their products recently. slimScroll doesn't occupy any visual space as it only appears on a user initiated mouse-over. User can drag the scrollbar or use mouse-wheel to change the scroll value.

Demo and deocumentation available here: [jQuery slimScroll docs](http://rocha.la/jQuery-slimScroll)

Copyright (c) 2011 Piotr Rochala (http://rocha.la)
Dual licensed under the MIT (http://www.opensource.org/licenses/mit-license.php) and GPL (http://www.opensource.org/licenses/gpl-license.php) licenses.
