---
title: narcissus-fe-eslint-plugin
categories:
  - 工程规范
tags:
  - 工程规范
author:
  name: 纳西索斯
  link: https://github.com/narcissus-ma/nm-spec
---

# narcissus-fe-eslint-plugin

## 安装

除了本包，你需要同时安装 [ESlint](https://eslint.org/)

```shell
$ npm install narcissus-fe-eslint-plugin eslint --save-dev
```

## 使用

### 引入插件

```js
// .eslintrc.js
module.exports = {
  plugin: ['narcissus-fe-eslint-config'],
  rules: {
    'narcissus-fe-eslint-plugin/no-secret-info': 'error',
  },
};
```

### 使用 presets

```js
// .eslintrc.js
module.exports = {
  extends: 'plugin:narcissus-fe-eslint-plugin/recommended',
};
```

## 支持的规则

- [`no-broad-semantic-versioning`](https://narcissus-ma.github.io/nm-spec/plugin/no-broad-semantic-versioning.html) 不要指定宽泛的版本范围
- [`no-http-url`](https://narcissus-ma.github.io/nm-spec/plugin/no-http-url.html) 使用 HTTPS 协议头的 URL，而不是 HTTP
- [`no-js-in-ts-project`](https://narcissus-ma.github.io/nm-spec/plugin/no-js-in-ts-project.html) 不要在 TS 项目中使用 JS
- [`no-secret-info`](https://narcissus-ma.github.io/nm-spec/plugin/no-secret-info.html) 不要在代码中直接设置 `password` `token` and `secret` 信息
