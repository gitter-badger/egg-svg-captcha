# egg-egg-svg-captcha

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

一个易用的 Egg.js  SVG 验证码插件，它并不依赖 C++ 拓展，而是纯 Node.js 模块。

[English](./README.md) | 简体中文

## 依赖说明

### 依赖的 egg 版本

egg-egg-svg-captcha 版本 | egg 1.x
--- | ---
1.x | 😁
0.x | ❌

### 依赖的插件
- [svg-captcha](https://github.com/hys1440248234/egg-svg-captcha)

## 开启插件

```js
// config/plugin.js
exports.eggSvgCaptcha = {
  enable: true,
  package: 'egg-egg-svg-captcha',
};
```

## 使用场景

- Why and What: 在使用 Egg.js 进行开发时没有一个好用的验证码插件，所以就自己根据 [svg-captcha](https://github.com/hys1440248234/egg-svg-captcha) 做了这个插件。
- How: 描述这个插件是怎样使用的，具体的示例代码，甚至提供一个完整的示例，并给出链接。

## 详细配置

请到 [config/config.default.js](config/config.default.js) 查看详细配置项说明。

## 单元测试

<!-- 描述如何在单元测试中使用此插件，例如 schedule 如何触发。无则省略。-->

## 提问交流

请到 [egg issues](https://github.com/hys1440248234/egg-svg-captcha/issues) 异步交流。

## License

[MIT](LICENSE)
