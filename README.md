# @omegion1npm/soluta-quidem-iste <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Give a regex, get a robust predicate function that tests it against a string. This will work even if `RegExp.prototype` is altered later.

## Getting started

```sh
npm install --save @omegion1npm/soluta-quidem-iste
```

## Usage/Examples

```js
var regexTester = require('@omegion1npm/soluta-quidem-iste');
var assert = require('assert');

var tester = regexTester('a');
assert.ok(tester('a'));
assert.notOk(tester('b'));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@omegion1npm/soluta-quidem-iste
[npm-version-svg]: https://versionbadg.es/ljharb/@omegion1npm/soluta-quidem-iste.svg
[deps-svg]: https://david-dm.org/ljharb/@omegion1npm/soluta-quidem-iste.svg
[deps-url]: https://david-dm.org/ljharb/@omegion1npm/soluta-quidem-iste
[dev-deps-svg]: https://david-dm.org/ljharb/@omegion1npm/soluta-quidem-iste/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@omegion1npm/soluta-quidem-iste#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@omegion1npm/soluta-quidem-iste.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@omegion1npm/soluta-quidem-iste.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@omegion1npm/soluta-quidem-iste.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@omegion1npm/soluta-quidem-iste
[codecov-image]: https://codecov.io/gh/ljharb/@omegion1npm/soluta-quidem-iste/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@omegion1npm/soluta-quidem-iste/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@omegion1npm/soluta-quidem-iste
[actions-url]: https://github.com/omegion1npm/soluta-quidem-iste/actions
