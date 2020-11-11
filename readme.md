# @melissa24/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@melissa24/tiny.svg)](https://www.npmjs.com/package/@melissa24/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@melissa24/tiny.svg)](https://www.npmjs.com/package/@melissa24/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @melissa24/tiny
```

## Usage

```js
const tiny = require("@melissa24/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
