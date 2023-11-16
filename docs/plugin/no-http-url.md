---
title: no-http-url
categories:
  - Eslint插件规范
tags:
  - Eslint插件规范
author:
  name: 纳西索斯
  link: https://github.com/narcissus-ma/nm-spec
---

# no-http-url

推荐将 HTTP 链接换为 HTTPS 链接。

## 规则内容

**错误代码**示例:

```js
var test = 'http://chenghuai.com';
var jsx = <img src="http://chenghuai.com">;
```

## 何时不适用

如果你的网站只支持 HTTP 时。
