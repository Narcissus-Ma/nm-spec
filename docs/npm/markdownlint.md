---
title: narcissus-fe-markdownlint-config
categories:
  - 工程规范
tags:
  - 工程规范
author:
  name: 纳西索斯
  link: https://github.com/narcissus-ma/nm-spec
---

# narcissus-fe-markdownlint-config

:::tip
纳西索斯 文档 规范
:::

支持配套的 [markdownlint 可共享配置](https://www.npmjs.com/package/markdownlint#optionsconfig)。

## 安装

需要先行安装 [markdownlint](https://www.npmjs.com/package/markdownlint)：

```bash
npm install narcissus-fe-markdownlint-config markdownlint --save-dev
```

## 使用

在 `.markdownlint.json` 中继承本包:

```json
{
  "extends": "narcissus-fe-markdownlint-config"
}
```
