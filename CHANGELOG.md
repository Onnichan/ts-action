<a name="3.2.3"></a>
## [3.2.3](https://github.com/cartant/ts-action/compare/v3.2.2...v3.2.3) (2018-01-27)

### Fixes

* Fix `types` filename in `package.json`.

<a name="3.2.2"></a>
## [3.2.2](https://github.com/cartant/ts-action/compare/v3.2.1...v3.2.2) (2017-11-18)

### Changes

* Minor documenation changes.

<a name="3.2.1"></a>
## [3.2.1](https://github.com/cartant/ts-action/compare/v3.2.0...v3.2.1) (2017-11-12)

### Bug Fixes

* **reducer**: Remove union with `undefined` from state. ([bd748f0](https://github.com/cartant/ts-action/commit/bd748f0))

<a name="3.2.0"></a>
## [3.2.0](https://github.com/cartant/ts-action/compare/v3.1.3...v3.2.0) (2017-11-12)

### Features

* **reducer**: Add a `reducer` method for creating reducer functions. ([d7e870e](https://github.com/cartant/ts-action/commit/d7e870e))

<a name="3.1.3"></a>
## [3.1.3](https://github.com/cartant/ts-action/compare/v3.1.2...v3.1.3) (2017-11-11)

### Changes

* **action**: Reset the `prototype` to that of `{}` rather than to `null`. ([3337e68](https://github.com/cartant/ts-action/commit/3337e68))

<a name="3.1.2"></a>
## [3.1.2](https://github.com/cartant/ts-action/compare/v3.1.1...v3.1.2) (2017-11-10)

### Changes

* **action**: The `options` are now optional and `empty` is the default. ([c91f3cd](https://github.com/cartant/ts-action/commit/c91f3cd))

<a name="3.1.1"></a>
## [3.1.1](https://github.com/cartant/ts-action/compare/v3.1.0...v3.1.1) (2017-11-10)

### Documentation

* Improvemed API documentation.

<a name="3.1.0"></a>
## [3.1.0](https://github.com/cartant/ts-action/compare/v3.0.1...v3.1.0) (2017-11-10)

### Feature

* **action**: Add a more terse overload that takes the `type` and `options` as separate parameters. ([083403f](https://github.com/cartant/ts-action/commit/083403f))

<a name="3.0.1"></a>
## [3.0.1](https://github.com/cartant/ts-action/compare/v3.0.0...v3.0.1) (2017-11-10)

### Changes

* The distribution now includes `.d.ts` files rather than `.ts` files. ([b5ebbbf](https://github.com/cartant/ts-action/commit/b5ebbbf))

<a name="3.0.0"></a>
## [3.0.0](https://github.com/cartant/ts-action/compare/v2.0.3...v3.0.0) (2017-11-09)

### Breaking Changes

* **action**: Removed the static `action` property from action creators. Instead, there's a `union` method for creating discriminated unions from action creators. ([22067fb](https://github.com/cartant/ts-action/commit/22067fb))

<a name="2.0.3"></a>
## [2.0.3](https://github.com/cartant/ts-action/compare/v2.0.2...v2.0.3) (2017-11-09)

### Bug Fixes

* **action**: Enforce `base` parameter types. ([e3128d2](https://github.com/cartant/ts-action/commit/e3128d2))
* **action**: Enforce `props` parameter type. ([1571ee4](https://github.com/cartant/ts-action/commit/1571ee4))

<a name="2.0.2"></a>
## [2.0.2](https://github.com/cartant/ts-action/compare/v2.0.1...v2.0.2) (2017-11-09)

### Bug Fixes

* **action**: Set `prototype` to `null` for `reactjs/redux` compatibility. ([9925f79](https://github.com/cartant/ts-action/commit/9925f79))

<a name="2.0.1"></a>
## [2.0.1](https://github.com/cartant/ts-action/compare/v2.0.0...v2.0.1) (2017-11-07)

### Changes

* Remove `tslib`.

<a name="2.0.0"></a>
## [2.0.0](https://github.com/cartant/ts-action/compare/v1.0.3...v2.0.0) (2017-11-06)

### Features

* Add support for inline base classes using `base`.

### Breaking Changes

* Default payloads and props have been removed.
* `create` has been removed.
* `params` has been removed.
* `empty` must be called when for action creators with no payload or props.
* Most interfaces have been removed.