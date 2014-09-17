# secure-random-uint

[![Build Status](https://img.shields.io/travis/KenanY/secure-random-uint.svg)](https://travis-ci.org/KenanY/secure-random-uint)

Generate a cryptographically secure uint.

## Example

``` javascript
var secureRandomUint = require('secure-random-uint');

secureRandomUint();
// =>
```

## Installation

``` bash
$ npm install secure-random-uint
```

## API

``` javascript
var secureRandomUint = require('secure-random-uint');
```

### `secureRandomUint()`

Returns a cryptographically secure _Number_ uint. Uses
[get-random-values](https://github.com/KenanY/get-random-values), so an _Error_
will be thrown if there is no secure random number generator available.