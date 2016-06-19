[![Build Status](https://semaphoreci.com/api/v1/nodeos/nodeos-barebones/branches/master/badge.svg)](https://semaphoreci.com/nodeos/nodeos-barebones)

# NodeOS barebones

This package will compile both [Node.js](http://nodejs.org) and
[Linux kernel](https://www.kernel.org/) using a cross-compiler for the desired
target. Used alone, it will generate a Linux image that by default will boots to
a Node.js [REPL](http://nodejs.org/api/repl.html) prompt.


## How to use

```sh
npm install
npm run build
```
