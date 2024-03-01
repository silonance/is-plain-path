# is-plain-path

> Check if a file path is a text file


## Install

```
$ npm install is-text-path
```


## Usage

```js
const isTextPath = require('is-plain-path');

isTextPath('source/unicorn.txt');
//=> true

isTextPath('source/unicorn.png');
//=> false
```