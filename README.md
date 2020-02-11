# egg-egg-svg-captcha

[![Join the chat at https://gitter.im/egg-svg-captcha/community](https://badges.gitter.im/egg-svg-captcha/community.svg)](https://gitter.im/egg-svg-captcha/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][codecov-image]][codecov-url]
[![David deps][david-image]][david-url]
[![Known Vulnerabilities][snyk-image]][snyk-url]
[![npm download][download-image]][download-url]

[npm-image]: https://img.shields.io/npm/v/egg-egg-svg-captcha.svg?style=flat-square
[npm-url]: https://npmjs.org/package/egg-egg-svg-captcha
[travis-image]: https://img.shields.io/travis/eggjs/egg-egg-svg-captcha.svg?style=flat-square
[travis-url]: https://travis-ci.org/eggjs/egg-egg-svg-captcha
[codecov-image]: https://img.shields.io/codecov/c/github/eggjs/egg-egg-svg-captcha.svg?style=flat-square
[codecov-url]: https://codecov.io/github/eggjs/egg-egg-svg-captcha?branch=master
[david-image]: https://img.shields.io/david/eggjs/egg-egg-svg-captcha.svg?style=flat-square
[david-url]: https://david-dm.org/eggjs/egg-egg-svg-captcha
[snyk-image]: https://snyk.io/test/npm/egg-egg-svg-captcha/badge.svg?style=flat-square
[snyk-url]: https://snyk.io/test/npm/egg-egg-svg-captcha
[download-image]: https://img.shields.io/npm/dm/egg-egg-svg-captcha.svg?style=flat-square
[download-url]: https://npmjs.org/package/egg-egg-svg-captcha

An easy-to-use egg.js SVG verification code plug-in that does not rely on C++ extensions, but pure node. js modules.

English | [简体中文](./README.zh_CN.md)

## Install

```bash
$ npm i egg-egg-svg-captcha --save
```

## Usage

```js
// {app_root}/config/plugin.js
exports.eggSvgCaptcha = {
  enable: true,
  package: 'egg-egg-svg-captcha',
};
```

## usage scenario

- Why and What: When I use Egg. Js to develop without a captcha plugin to use, so their according to [SVG - captcha] did this plugin (https://github.com/hys1440248234/egg-svg-captcha).
- How: [todo]

## Configuration

```js
// {app_root}/config/config.default.js
exports.eggSvgCaptcha = {
};
```

see [config/config.default.js](config/config.default.js) for more detail.

## Example

<!-- example here todo -->

## Questions & Suggestions

Please open an issue [here](https://github.com/hys1440248234/egg-svg-captcha/issues).

## License

[MIT](LICENSE)
