<div align="center" style="text-align: center;">
  <h1 style="border-bottom: none;">web-apis-with-demo</h1>

  <p>A curated list of demos for various Web APIs</p>
</div>

<hr />

[![Version][version-badge]][version-url]
[![Node version][node-version-badge]][node-version-url]
[![MIT License][mit-license-badge]][mit-license-url]

[![Downloads][downloads-badge]][downloads-url]
[![Total downloads][total-downloads-badge]][downloads-url]
[![Packagephobia][packagephobia-badge]][packagephobia-url]
[![Bundlephobia][bundlephobia-badge]][bundlephobia-url]

[![Build Status][travis-badge]][travis-url]
[![CircleCI][circleci-badge]][circleci-url]
[![Dependency Status][daviddm-badge]][daviddm-url]
[![codecov][codecov-badge]][codecov-url]
[![Coverage Status][coveralls-badge]][coveralls-url]

[![codebeat badge][codebeat-badge]][codebeat-url]
[![Codacy Badge][codacy-badge]][codacy-url]
[![Code of Conduct][coc-badge]][coc-url]

> Better greeting message

## Table of contents

- [Table of contents](#table-of-contents)
- [Pre-requisites](#pre-requisites)
- [Setup](#setup)
  - [Install](#install)
  - [Usage](#usage)
    - [Node.js](#nodejs)
    - [Native ES modules or TypeScript](#native-es-modules-or-typescript)
- [API Reference](#api-reference)
  - [greeting([name])](#greetingname)
  - [greetingSync([name])](#greetingsyncname)
- [License](#license)

## Pre-requisites

- [Node.js][nodejs-url] >= 10.11.0
- [NPM][npm-url] >= 6.4.1 ([NPM][npm-url] comes with [Node.js][nodejs-url] so there is no need to install separately.)

## Setup

### Install

```sh
# Install via NPM
$ npm install --save web-apis-with-demo
```

### Usage

#### Node.js

```js
const greeting = require('web-apis-with-demo');
```

#### Native ES modules or TypeScript

```ts
// @ts-check

import greeting from 'web-apis-with-demo';
```

## API Reference

### greeting([name])

- `name` <[string][string-mdn-url]> Name of the person to greet at.
- returns: <[Promise][promise-mdn-url]<[string][string-mdn-url]>> Promise which resolves with a greeting message.

### greetingSync([name])

This methods works the same as `greeting(name)` except that this is the synchronous version.

## License

[MIT License](https://motss.mit-license.org/) © Rong Sen Ng

<!-- References -->
[typescript-url]: https://github.com/Microsoft/TypeScript
[nodejs-url]: https://nodejs.org
[npm-url]: https://www.npmjs.com
[node-releases-url]: https://nodejs.org/en/download/releases

<!-- MDN -->
[array-mdn-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array
[boolean-mdn-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean
[function-mdn-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function
[map-mdn-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map
[number-mdn-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number
[object-mdn-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object
[promise-mdn-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise
[regexp-mdn-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp
[set-mdn-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set
[string-mdn-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String

<!-- Badges -->
[version-badge]: https://flat.badgen.net/npm/v/web-apis-with-demo
[node-version-badge]: https://flat.badgen.net/npm/node/web-apis-with-demo
[mit-license-badge]: https://flat.badgen.net/npm/license/web-apis-with-demo

[downloads-badge]: https://flat.badgen.net/npm/dm/web-apis-with-demo
[total-downloads-badge]: https://flat.badgen.net/npm/dt/web-apis-with-demo?label=total%20downloads
[packagephobia-badge]: https://flat.badgen.net/packagephobia/install/web-apis-with-demo
[bundlephobia-badge]: https://flat.badgen.net/bundlephobia/minzip/web-apis-with-demo

[travis-badge]: https://flat.badgen.net/travis/motss/web-apis-with-demo
[circleci-badge]: https://flat.badgen.net/circleci/github/motss/web-apis-with-demo
[daviddm-badge]: https://flat.badgen.net/david/dep/motss/web-apis-with-demo
[codecov-badge]: https://flat.badgen.net/codecov/c/github/motss/web-apis-with-demo?label=codecov
[coveralls-badge]: https://flat.badgen.net/coveralls/c/github/motss/web-apis-with-demo?label=coveralls

[codebeat-badge]: https://codebeat.co/badges/123
[codacy-badge]: https://api.codacy.com/project/badge/Grade/123
[coc-badge]: https://flat.badgen.net/badge/code%20of/conduct/pink

<!-- Links -->
[version-url]: https://www.npmjs.com/package/web-apis-with-demo
[node-version-url]: https://nodejs.org/en/download
[mit-license-url]: https://github.com/motss/web-apis-with-demo/blob/master/LICENSE

[downloads-url]: http://www.npmtrends.com/web-apis-with-demo
[packagephobia-url]: https://packagephobia.now.sh/result?p=web-apis-with-demo
[bundlephobia-url]: https://bundlephobia.com/result?p=web-apis-with-demo

[travis-url]: https://travis-ci.org/motss/web-apis-with-demo
[circleci-url]: https://circleci.com/gh/motss/web-apis-with-demo/tree/master
[daviddm-url]: https://david-dm.org/motss/web-apis-with-demo
[codecov-url]: https://codecov.io/gh/motss/web-apis-with-demo
[coveralls-url]: https://coveralls.io/github/motss/web-apis-with-demo?branch=master

[codebeat-url]: https://codebeat.co/projects/github-com-motss-web-apis-with-demo-master
[codacy-url]: https://www.codacy.com/app/motss/web-apis-with-demo?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=motss/web-apis-with-demo&amp;utm_campaign=Badge_Grade
[coc-url]: https://github.com/motss/web-apis-with-demo/blob/master/CODE_OF_CONDUCT.md
