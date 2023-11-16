---
title: no-broad-semantic-versioning
categories:
  - Eslint插件规范
tags:
  - Eslint插件规范
author:
  name: 纳西索斯
  link: https://github.com/narcissus-ma/nm-spec
---

# no-broad-semantic-versioning

:::tip
纳西索斯 Eslint Plugin 插件 规范
:::

不要在 `package.json` 中使用太过宽泛的版本指定方式，包括 `*`、`x` 和 `> x` 。

## 规则内容

参照 [https://docs.npmjs.com/about-semantic-versioning](https://docs.npmjs.com/about-semantic-versioning)。

使用 `*`、 `x` 和 `> x` 指定版本会被警告。
