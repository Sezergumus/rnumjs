# What is this?

This is a light-weight module which you can generate random numbers easily.

# Installation

```
npm i rnumjs --save
// or
yarn add rnumjs
```

## Usage

```
const rnumjs = require('rnumjs')
// or
import { randomNumber } from 'rnumjs'

rnumjs.randomNumber(min, max, dec)
```

* min [number][1] Lower bound (optional, default `0`)
* max [number][1] Higher bound (optional, default `10`)
* dec [number][1] Rounds number to decimals (optional, default `0`)


[1]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number