---
title: html笔记——头部篇
author: 胖娃娃树下
date: 2017/07/03
---
# html笔记——头部

## 1. ``<head></head>``标签内包含的元素
- `<title>`: 标题
- `<link>`： 引用external CSS文件等
- ``<style>``：存放internal CSS
- ``<script>``： 存放internal 或 引用external js文件
- ``<meta>``： 元信息
- `<base>`: 定义所有URL的默认连接基础

## 2. 各标签用法
- `<title>` 文字放在`<title>`与`</title>`之间，不需要引号。
- `<link rel="stylesheet" type="text/css" href="mystyle.css">` `rel:relationship` `type:MIME_TYPE` `href:hyperlink Reference` [This](http://www.runoob.com/tags/tag-link.html) for more information.
- ``<base href="http://www.runoob.com/images/" target="_blank">`` `target`定义链接打开位置，如新标签/新窗口/替换本标签等 [This](http://www.runoob.com/tags/tag-base.html) for more information.
- `<style>`: 存放页面内部CSS样式表。
- `<script>`: 既可包含脚本语句，也可以通过 "src" 属性指向外部脚本文件。

            <script src="myScript.js"></script>  
            or
            <script>
              function myFunction()
              {
                  document.getElementById("demo").innerHTML="我的第一个 JavaScript 函数";
              }  
            需要注意：`<script>`既可以在`<head>`中也可以在`<body>`中  

- `<meta>`
  - name
    - author
    - description
    - generator
    - keywords
    - **viewport** `content='width=device-width,initial-scale=1.0'` [This](http://www.runoob.com/css/css-rwd-viewport.html) for more information.
  - [http-equiv](http://www.runoob.com/tags/att-meta-http-equiv.html)
  - charset
