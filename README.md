# Bifrost

[![Bower](https://img.shields.io/bower/v/bifrost-color.svg)](https://github.com/thibmaek/Bifrost)
[![npm](https://img.shields.io/npm/v/bifrost-color.svg?maxAge=2592000)]() [![Build Status](https://travis-ci.org/thibmaek/Bifrost.svg?branch=master)](https://travis-ci.org/thibmaek/Bifrost)

Bifrost is an easy to use and highly configurable color palette for your Sass projects.  

It uses the SCSS syntax with human-readable variable naming provided by [Sip's](http://theolabrothers.com) handy naming gimmick.

Colors are provided as rgba format to make every value easily adjustable.

<br>

## Usage

Install it from npm (preferred) or bower:

```console
npm install -D bifrost-color
bower install --save-dev bifrost-color
```

Use it in your Sass files by calling the function and passing the correct
parameters:

```scss
/**
 * @param {string} color-group
 * @param {string} named-color
 */

ul li {
  color: bifrost(whites, narvik);
}
```

[See an example of bifrost here](http://codepen.io/thibmaek/pen/WvQoLg)

![Preview](http://imgur.com/hAoRiO2.png)

## Contributing

Be sure to add your own colors to help improve the list. Make sure you format them as rgba and respect the rules from scss-lint.

Run tests locally with `npm install && npm test` and submit a PR.
