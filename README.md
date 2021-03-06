# reflux-core

A simple core library for unidirectional dataflow architecture inspired by [Flux](http://facebook.github.io/react/blog/2014/05/06/flux.html). This module does not depend on React and may be used together with other view engine libraries.

[![NPM Version][npm-image]][npm-url]
[![NPM Downloads][downloads-image]][npm-url]
[![Dependencies][dependencies-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Gratipay][gratipay-image]][gratipay-url]

For an overview of reflux with react extensions, look at the [refluxjs repository][refluxjs-url].

## Installation

You can currently install the package as a npm package.

### NPM

The following command installs `reflux-core` as a npm package:

    npm install reflux-core

### ES5

Like React, Reflux depends on an es5-shim for older browsers. The es5-shim.js from [kriskowal's es5-shim](https://github.com/kriskowal/es5-shim) provides everything required.

## Colophon

[List of contributors](https://github.com/reflux/reflux-core/graphs/contributors) is available on Github.

This project is licensed under [BSD 3-Clause License](http://opensource.org/licenses/BSD-3-Clause). Copyright (c) 2014, Mikael Brassman.

For more information about the license for this particular project [read the LICENSE.md file](LICENSE.md).

This project uses [eventemitter3](https://github.com/3rd-Eden/EventEmitter3), is currently MIT licensed and [has it's license information here](https://github.com/3rd-Eden/EventEmitter3/blob/master/LICENSE).

[npm-image]: http://img.shields.io/npm/v/reflux-core.svg
[downloads-image]: http://img.shields.io/npm/dm/reflux-core.svg
[dependencies-image]: http://img.shields.io/david/reflux/reflux-core.svg
[npm-url]: https://www.npmjs.org/package/reflux-core
[travis-image]: http://img.shields.io/travis/spoike/reflux-core/master.svg
[travis-url]: https://travis-ci.org/spoike/reflux-core
[gratipay-image]: http://img.shields.io/gratipay/spoike.svg
[gratipay-url]: https://gratipay.com/spoike/
[refluxjs-url]: https://github.com/reflux/refluxjs#refluxjs
