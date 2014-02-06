# Archetype-u-size [![Build Status](https://secure.travis-ci.org/Archetype-CSS/u-size.png?branch=master)](http://travis-ci.org/Archetype-CSS/u-size) [![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)](http://gruntjs.com/)

Archetype utilities for providing intrinsic and proportional widths

## Installation
  * [Bower](http://bower.io): {{coming soon}}
  * Git: `git clone https://github.com/Archetype-CSS/u-size.git`

## Use

### Intrinsic Widths
  * `u-sizeWrap` - Shrink wrap an element via float left
  * `u-sizeWrapRight` - Shrink wrap an element via float right
  * `u-sizeFill` - Force an element to fill remaining space
  * `u-sizeFull` - Force an element to the width of its parent

### Proportional Widths
  * `u-sizeXofY` - Specify an explicit width (percentage of parent container)

`X` must be an integer < `y`

`Y` can be either 2, 3, 4, 6, 8, 10, or 12

## Run the Test Locally

```bash
git clone https://github.com/Archetype-CSS/u-size.git
cd u-size
npm install
grunt
```

### Browser Suport
  * Chrome (latest)
  * Firefox (4+)
  * Opera (latest)
  * Safari (5+)
  * Internet Explorer (8+)

#### License
[MIT](/LICENSE.md)

