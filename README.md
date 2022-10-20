# @tringuyexn/tiny

![npm (scoped)](https://img.shields.io/npm/v/@tringuyexn/tiny)
![npm bundle size](https://img.shields.io/bundlephobia/min/@tringuyexn/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @tringuyexn/tiny
```

## Usage

```js
const tiny = require("@tringuyexn/tiny");

tiny("So much space!)
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
