---
title: 在 Fluid 使用更多图标的详细过程
author: Vince
abbrlink: 471286c7
date: 2020-04-14 22:11:03
tags:
 - 教程
categories:
  - 教程分享
index_img: https://cdn.vince.pub/blog-file/photo/site-0625/index.png
banner_img: https://cdn.vince.pub/blog-file/photo/site-0625/index.png
excerpt: Fluid 在2020/4/5之前的版本使用的图标库是 FontAwesome，在之后的版本使用 Iconfont。另外内容已经 PR 到文档中。
---

# 在 Fluid 使用更多图标的详细过程

## 前言
Fluid 在2020/4/5之前的版本使用的图标库是 FontAwesome，在之后的版本使用 Iconfont。相对而言，Iconfont 更适合我们的使用习惯，但是在 Iconfont 中，没用相关图标库项目共享功能，且主题作者也不能内置全部图标，只内置了部分社交图标，不过据了解，后续会更新更多图标。这篇帖子主要介绍如何引入更多图标，另外内容已经 PR 到 **[Fluid Doc](https://hexo.fluid-dev.com/docs/icon/)** 中。

## 关于 font-class 引用
主题图标使用 font-class 引用，font-class 是 unicode 使用方式的一种变种，比起 unicode 更加便捷和直观。iconfont 支持在线引用和本地引用。以下内容基于 font-class 引用。

### 本地应用
首先需要获取图标的 CSS 文件，将文件放到主题目录 'source/css' 中，在主题配置文件 custom_css 项中添加 CSS 文件路径。

实例

``` 
custom_css: /css/custom.css
```

在相关文件、页面，将 icon- 开头的那行填入 css class 即可。比如： iconfont icon-email 。

## Iconfont 在线引用
Iconfont支持用户创建项目来管理和使用图标库，在 图标管理-我的项目 中即可管理和创建项目。将所需图标添加至购物车，再通过购物车添加至所创建的项目中。在项目中可以下载至本地与生成在线链接，Iconfont 支持在阿里云的 CDN 中生成 CSS 或 JS 文件用来调用。

生成在线链接后，通过自定义 CSS调用，将 icon- 开头的那行填入 css class 即可，例如 iconfont icon-email）。在每次有删减项目中图标库目录时，需要在项目中点击重新生成链接才可生效。