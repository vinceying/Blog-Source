---
title: jsDelivr-CDN 相关配置
author: Vince
banner_img: https://cdn.jsdelivr.net/gh/vinceying/blog-file/photo/2667741f1.jpg
index_img: https://cdn.jsdelivr.net/gh/vinceying/blog-file/photo/2667741f1.jpg
abbrlink: 2667741f
date: 2020-04-06 20:54:14
tags:
  - 说明
categories:
  - 网站
excerpt: 使用了 Github 搭建了一个新的项目，用作相关文件处理，主要用于图床服务，使用 jsDelivr CDN 来加载
---

# jsDelivr-CDN 相关配置
>jsDelivr – Open Source CDNfree, fast, and reliable

[![](https://data.jsdelivr.com/v1/package/gh/vinceying/blog-file/badge)](https://www.jsdelivr.com/package/gh/vinceying/blog-file)

使用了 Github 搭建了一个新的项目，用作相关文件处理，主要用于图床服务，使用 jsDelivr CDN 来加载。

## 官方配置

// load any GitHub release, commit, or branch
// note: we recommend using npm for projects that support it
```
https://cdn.jsdelivr.net/gh/user/repo@version/file
```

## 个人文件服务
**图片**

链接
```
https://cdn.jsdelivr.net/gh/vinceying/blog-file@master/photo/
```
实例
```
https://cdn.jsdelivr.net/gh/vinceying/blog-file@master/photo/2667741f.jpg
```
Markdown 引用
```
![2667741f.jpg](https://cdn.jsdelivr.net/gh/vinceying/blog-fil@master/photo/2667741f.jpg)
```

*其它文件服务暂未更新
