# Myprotein Discount Codes

A collection of [Myprotein discount codes](https://www.wethrift.com/myprotein). We use these for testing [Myprotein UK](https://www.wethrift.com/myprotein), [Myprotein US](https://www.wethrift.com/myprotein-us), [Myprotein Singapore](https://www.wethrift.com/myprotein-singapore), [Myprotein Australia](https://www.wethrift.com/myprotein-australia) and [Myprotein Hong Kong](https://www.wethrift.com/myprotien-hongkong) pages at Wethrift.com.

## Installation

Install `myprotein-discount-codes` via NPM:

```sh
npm install myprotein-discount-codes
```

## Usage

The package contains in array of objects representing discount codes.

In Node:

```js
var codes = require('myprotein-discount-codes')

console.log(codes)

// [
//   {
//     site: 'https://www.myprotein.com',
//     discount_code: 'BENJAMINMP',
//     offer: '30% discount'
//   },
//   {
//     site: 'https://www.myprotein.com',
//     discount_code: 'HKLOVE',
//     offer: '50% off'
//   }...
```

## About

Myprotein-discount-codes was built by the team at [Wethrift](https://www.wethrift.com) ([development links](https://wethrift.github.io)) to assist with testing.

<https://www.wethrift.com>
