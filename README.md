# tiny_npm_package
Make a tiny npm package to remove spaces from strings and publish it :)

## Install

```
$ npm install @daizy_1999/tiny
```

## Usage

```js
const tiny = require("@daizy_1999/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
