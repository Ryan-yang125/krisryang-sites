---
title: "JavaScript编译原理"
subtitle: "JS引擎是如何运作的"
date: 2020-12-06
categories: ['Tech']
---

### 引擎是如何运作的

这是我目前为止对JavaScript编译原理（不考虑优化）的大致理解:

![v8](/img/post-v8.png)

### 词法作用域

这其中我们着重关注词法作用域的规则，包括var/let的区别，提升，闭包等概念

![field](/img/post-field.png)

至此，关于JavaScript词法部分的内容基本告一段落。