# pad-left [![NPM version](https://img.shields.io/npm/v/pad-left.svg)](https://www.npmjs.com/package/pad-left) [![NPM downloads](https://img.shields.io/npm/dm/pad-left.svg?style=flat)](https://npmjs.org/package/pad-left) [![Build Status](https://img.shields.io/travis/jonschlinkert/pad-left.svg)](https://travis-ci.org/jonschlinkert/pad-left)

> Left pad a string with zeros or a specified string. Fastest implementation.

You might also be interested in [word-wrap](https://github.com/jonschlinkert/word-wrap).

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install pad-left --save
```

## Usage

```js
var pad = require('pad-left');
pad(  '4', 4, '0') // 0004
pad( '35', 4, '0') // 0035
pad('459', 4, '0') // 0459
```

## Benchmarks

```sh
#1: default-ch-10
  pad-left x 10,705,793 ops/sec ±1.85% (93 runs sampled)
  left-pad x 6,010,404 ops/sec ±0.81% (94 runs sampled)

  fastest is pad-left
#2: default-ch-100
  pad-left x 11,304,021 ops/sec ±0.94% (96 runs sampled)
  left-pad x 1,258,996 ops/sec ±0.94% (93 runs sampled)

  fastest is pad-left
#3: default-num-10
  pad-left x 9,812,997 ops/sec ±0.65% (95 runs sampled)
  left-pad x 5,593,133 ops/sec ±0.87% (95 runs sampled)

  fastest is pad-left
#4: default-num-100
  pad-left x 11,231,420 ops/sec ±0.83% (95 runs sampled)
  left-pad x 1,175,700 ops/sec ±0.89% (93 runs sampled)

  fastest is pad-left
```

## Related projects

You might also be interested in these projects:

* [align-text](https://www.npmjs.com/package/align-text): Align the text in a string. | [homepage](https://github.com/jonschlinkert/align-text)
* [center-align](https://www.npmjs.com/package/center-align): Center-align the text in a string. | [homepage](https://github.com/jonschlinkert/center-align)
* [justified](https://www.npmjs.com/package/justified): Wrap words to a specified length and justified the text. | [homepage](https://github.com/jonschlinkert/justified)
* [pad-right](https://www.npmjs.com/package/pad-right): Right pad a string with zeros or a specified string. Fastest implementation. | [homepage](https://github.com/jonschlinkert/pad-right)
* [repeat-string](https://www.npmjs.com/package/repeat-string): Repeat the given string n times. Fastest implementation for repeating a string. | [homepage](https://github.com/jonschlinkert/repeat-string)
* [right-align](https://www.npmjs.com/package/right-align): Right-align the text in a string. | [homepage](https://github.com/jonschlinkert/right-align)
* [right-align-keys](https://www.npmjs.com/package/right-align-keys): Right align the keys of an object. | [homepage](https://github.com/jonschlinkert/right-align-keys)
* [right-align-values](https://www.npmjs.com/package/right-align-values): Right align the values of a given property for each object in an array. Useful… [more](https://www.npmjs.com/package/right-align-values) | [homepage](https://github.com/jonschlinkert/right-align-values)
* [right-pad-keys](https://www.npmjs.com/package/right-pad-keys): Right pad the keys of an object. | [homepage](https://github.com/jonschlinkert/right-pad-keys)
* [right-pad-values](https://www.npmjs.com/package/right-pad-values): Right pad the values of a given property for each object in an array. Useful… [more](https://www.npmjs.com/package/right-pad-values) | [homepage](https://github.com/jonschlinkert/right-pad-values)
* [word-wrap](https://www.npmjs.com/package/word-wrap): Wrap words to a specified length. | [homepage](https://github.com/jonschlinkert/word-wrap)

## Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/jonschlinkert/pad-left/issues/new).

## Building docs

Generate readme and API documentation with [verb](https://github.com/verbose/verb):

```sh
$ npm install verb && npm run docs
```

Or, if [verb](https://github.com/verbose/verb) is installed globally:

```sh
$ verb
```

## Running tests

Install dev dependencies:

```sh
$ npm install -d && npm test
```

## Author

**Jon Schlinkert**

* [github/jonschlinkert](https://github.com/jonschlinkert)
* [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

## License

Copyright © 2016 [Jon Schlinkert](https://github.com/jonschlinkert)
Released under the [MIT license](https://github.com/jonschlinkert/pad-left/blob/master/LICENSE).

***

_This file was generated by [verb](https://github.com/verbose/verb), v0.9.0, on March 23, 2016._