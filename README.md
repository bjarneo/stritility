strility
--
![Travis](https://travis-ci.org/bjarneo/strility.svg?branch=master)

Strility is a string manipulation library

[Work in progress]

Usage
--

```bash
$ npm i --save strility
```

Api
--
```js
const { isUpperCase } = require('strility');

isUpperCase('string')
```
* string, the input string. 
* returns true or false

```js
const { isLowerCase } = require('strility');

isLowerCase('string')
```
* string, the input string. 
* returns true or false

```js
const { isString } = require('strility');

isString('string')
```
* string, the input string. 
* returns true or false

```js
// Uses the Fisher-Yates algorithm
const { shuffle } = require('strility');

shuffle('string') // 'trsgni'
```
* string, the input string. 
* returns shuffled string

```js
const { chars } = require('strility');

chars('string') // [ 's', 'r', 'i', 'n', 'g' ]
```
* string, the input string. 
* returns array of characters

Tests
--
```bash
$ npm test
```

Contribution
--
Contributions are appreciated.

License
--
MIT-licensed. See LICENSE.
