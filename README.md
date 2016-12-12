# generator-redux-app

[![NPM version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Test coverage][coveralls-image]][coveralls-url]
[![Dependency Status][david_img]][david_site]

> Scaffold out a redux app

Using [chentsulin/redux-boilerplate](https://github.com/chentsulin/redux-boilerplate) as template. Extend [counter examples](https://github.com/rackt/redux/tree/master/examples/counter) with [react-router](https://github.com/rackt/react-router). And use [jest](https://facebook.github.io/jest/).

## Install

```sh
$ npm install -g generator-redux-app
```

> Note: `generator-redux-app` is a [yeoman](http://yeoman.io/) generator, so you must have global `yo` installed, too.

```sh
$ npm install -g yo
```

## Usage

```sh
$  mkdir your-app-name && cd your-app-name && yo redux-app
```

## Troubleshooting

#### TypeError: this.env.adapter.prompt(...).then is not a function

Please upgrade your global `yo` npm module using `npm install -g yo`.

## License

MIT © [C.T. Lin](https://github.com/chentsulin)

[npm-image]: https://badge.fury.io/js/generator-redux-app.svg
[npm-url]: https://npmjs.org/package/generator-redux-app
[travis-image]: https://travis-ci.org/chentsulin/generator-redux-app.svg
[travis-url]: https://travis-ci.org/chentsulin/generator-redux-app
[coveralls-image]: https://coveralls.io/repos/chentsulin/generator-redux-app/badge.svg?branch=master&service=github
[coveralls-url]: https://coveralls.io/r/chentsulin/generator-redux-app?branch=master
[david_img]: https://david-dm.org/chentsulin/generator-redux-app.svg
[david_site]: https://david-dm.org/chentsulin/generator-redux-app
