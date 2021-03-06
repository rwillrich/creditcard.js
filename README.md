# creditcard.js

[![Build Status](https://api.travis-ci.org/ContaAzul/creditcard.js.svg?branch=master)](https://travis-ci.org/ContaAzul/creditcard.js)
[![Dependency Status](https://david-dm.org/ContaAzul/creditcard.js.svg)](https://david-dm.org/Semantic-Org/ContaAzul/creditcard.js)
[![devDependency Status](https://david-dm.org/ContaAzul/creditcard.js/dev-status.svg)](https://david-dm.org/ContaAzul/creditcard.js#info=devDependencies)

> A simple credit cards validation library in JavaScript.

<img src="assets/images/credit-card-logo.png" alt="creditcard.js" />
## Install

You can [download the zip file](https://github.com/contaazul/creditcard.js/archive/master.zip) or use NPM and Bower.

### NPM

```sh
$ npm install --save-dev creditcard.js
```

### Bower

```sh
$ bower install creditcard.js --save
```

## Usage

In the browser:

```javascript
var obj = new CreditCard();
obj.getCreditCardNameByNumber('4539578763621486'); // returns 'Visa'
```

In the server:

```javascript
var creditcard = require('creditcard.js');
credit.getCreditCardNameByNumber('4539578763621486'); // returns 'Visa'
```

### Methods

#### obj`.validadeExpiryDate()`

Returns whether the value is `true` or `false`.

#### obj`.validadeCreditCard()`

Returns whether the value is `true` or `false`.

#### obj`.validadeSecuryCode()`

Returns whether the value is `true` or `false`.

#### obj`.getCreditCardNameByNumber()`

Returns a `String` with the credit card name.

## Browser support

| <img src="http://i.imgur.com/dJC1GUv.png" width="48px" height="48px" alt="Chrome logo"> | <img src="http://i.imgur.com/o1m5RcQ.png" width="48px" height="48px" alt="Firefox logo"> | <img src="http://i.imgur.com/8h3iz5H.png" width="48px" height="48px" alt="Internet Explorer logo"> | <img src="http://i.imgur.com/iQV4nmJ.png" width="48px" height="48px" alt="Opera logo"> | <img src="http://i.imgur.com/j3tgNKJ.png" width="48px" height="48px" alt="Safari logo"> |
|:---:|:---:|:---:|:---:|:---:|
| Latest ✔ | Latest ✔ | 9+ ✔ | Latest ✔ | 8+ ✔ |

## License

MIT © Conta Azul
