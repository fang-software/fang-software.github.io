---
layout: post
title: "Chrome安装vue-devtools"
categories: js
author: "fang-software"
meta: "vue"
date: 2018-09-28
---

1. clone [vue-devtools](https://github.com/vuejs/vue-devtools)

2. npm install

3. npm run build

4. 修改 vue-devtools/shells/chrome/manifest.json文件，将 persistent改成 true
![img1](/assets/img/vue-devtools/img1.png "img1")

5. 打开chrome，输入chrome://extensions/，进入到chrome扩展程序设置页面
    * 打开右上角的“开发者模式”
    ![img2](/assets/img/vue-devtools/img2.png "img2")

    * 点击“加载已解压的扩展程序”
    ![img3](/assets/img/vue-devtools/img3.png "img3")

    * 选择 vue-devtools/shells/chrome
    ![img4](/assets/img/vue-devtools/img4.png "img4")

    * 注意：勾选“允许访问文件网址”
    ![img5](/assets/img/vue-devtools/img5.png "img5")