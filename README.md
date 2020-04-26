# jstransformer-css-whitespace

[Whitespace significant CSS](http://npm.im/css-whitespace) support for [JSTransformers](http://github.com/jstransformers).

[![Build Status](https://img.shields.io/travis/jstransformers/jstransformer-css-whitespace/master.svg)](https://travis-ci.org/jstransformers/jstransformer-css-whitespace)
[![Coverage Status](https://img.shields.io/codecov/c/github/jstransformers/jstransformer-css-whitespace/master.svg)](https://codecov.io/gh/jstransformers/jstransformer-css-whitespace)
[![Dependency Status](https://img.shields.io/david/jstransformers/jstransformer-css-whitespace/master.svg)](http://david-dm.org/jstransformers/jstransformer-css-whitespace)
[![NPM version](https://img.shields.io/npm/v/jstransformer-css-whitespace.svg)](https://www.npmjs.org/package/jstransformer-css-whitespace)

## Installation

    npm install jstransformer-css-whitespace

## API

```js
var css = require('jstransformer')(require('jstransformer-css-whitespace'))

css.render('body\n  color: #888\n').body
//=> 'body { color: #888; }'
```

## License

MIT
