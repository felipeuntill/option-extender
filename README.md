# OptionExtender

  Fast, tiny and useful helper to replace your properties..

  [![NPM Version][npm-image]][npm-url]
  [![NPM Downloads][downloads-image]][downloads-url]
  [![Linux Build][travis-image]][travis-url]

## Installation

```bash
$ npm install optionextender
```

## Quick Start

```js
var optionExtender = require('optionextender')

var previsouly = { 
    name : 'previously name'  
};
var replace = {  
    name : 'replace name' 
};

console.log(optionExtender(previsouly, replace));
```

## Tests

  To run the test suite, first install the dependencies, then run `npm test`:

```bash
$ npm install
$ npm test
```

## Features

  * Properties substitution

## People

The author of optionextender is [Felipe Assunção](https://github.com/felipeuntill)

## License

  [GNU GENERAL PUBLIC LICENSE](LICENSE)

[npm-image]: https://img.shields.io/npm/v/optionextender.svg
[npm-url]: https://npmjs.org/package/optionextender
[downloads-image]: https://img.shields.io/npm/dm/optionextender.svg
[downloads-url]: https://npmjs.org/package/optionextender
[travis-image]: https://travis-ci.org/felipeuntill/optionExtender.svg
[travis-url]: https://travis-ci.org/felipeuntill/optionExtender
