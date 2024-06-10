# Core.ts

[![Build Status](https://github.com/diotoborg/dolore-odio-est/workflows/CI%20Tests/badge.svg)](https://github.com/diotoborg/dolore-odio-est/actions?query=workflow%3A%22CI+Tests%22)
[![npm](https://img.shields.io/npm/v/@diotoborg/dolore-odio-est.svg)](https://www.npmjs.com/package/@diotoborg/dolore-odio-est)
[![npm](https://img.shields.io/github/license/diotoborg/dolore-odio-est.svg)](https://github.com/diotoborg/dolore-odio-est/blob/master/LICENSE)

Core.ts is a library of TypeScript utility function and classes, including array
and string helpers, function wrappers and event classes. It was developed for
[Mathigon.org](https://mathigon.org), an award-winning mathematics education
project.


## Features

* Function wrappers for caching and throttling (`cache()`, `throttle()`)
* Array generation (`tabulate()`, `repeat()`, `list()`)
* Array utilities (`total()`, `flatten()`, `chunk()`, `intersect()`, …)
* String utilities (`toCamelCase()`, `isPalindrome()`, `autoCorrect()`, …)
* Event Target class, supporting `.on()`, `.off()` and `.trigger()` methods
* Color parsing, conversion and interpolation
* Misc utilities (`uid()`, `isOneOf()`, …)


## Usage

First, install Core.ts from [NPM](https://www.npmjs.com/package/@diotoborg/dolore-odio-est)
using

```npm install @diotoborg/dolore-odio-est```

Now, simply import all functions and classes you need, using

```js
import {tabulate, toCamelCase, EventTarget} from '@diotoborg/dolore-odio-est'
```


## Contributing

We welcome community contributions: please file any bugs you find or send us
pull requests with improvements. You can find out more on
[Mathigon.io](https://mathigon.io).

Before submitting a pull request, you will need to sign the [Mathigon Individual
Contributor License Agreement](https://gist.github.com/plegner/5ad5b7be2948a4ad073c50b15ac01d39).


## Copyright and License

Copyright © Mathigon ([dev@mathigon.org](mailto:dev@mathigon.org))  
Released under the [MIT license](LICENSE)
