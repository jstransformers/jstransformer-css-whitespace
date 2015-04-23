# jstransformer-css-whitespace

[Whitespace significant CSS](https://github.com/reworkcss/css-whitespace) support for [JSTransformers](https://github.com/jstransformers/jstransformer).

[![Build Status](https://img.shields.io/travis/jstransformers/jstransformer-css-whitespace/master.svg)](https://travis-ci.org/jstransformers/jstransformer-css-whitespace)
[![Coverage Status](https://img.shields.io/coveralls/jstransformers/jstransformer-css-whitespace/master.svg)](https://coveralls.io/r/jstransformers/jstransformer-css-whitespace?branch=master)
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
