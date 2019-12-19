---
layout: post
title: "JavaScript函数防抖和节流"
categories: js
author: "fang-software"
meta: "js"
date: 2019-12-19
---

## 一、防抖(debounce)
1. 基本原理
    * `防抖`指触发事件后，把触发非常频繁的事件合并成一次去执行。即在指定时间内只执行一次回调函数，如果在指定的时间内又触发了该事件，则回调函数的执行时间会基于此刻重新开始计算
    * 生活案例解释
        - 以我们生活中乘车刷卡的情景举例，只要乘客不断地在刷卡，司机师傅就不能开车，乘客刷卡完毕之后，司机会等待几分钟，确定乘客坐稳再开车。如果司机在最后等待的时间内又有新的乘客上车，那么司机等乘客刷卡完毕之后，还要再等待一会，等待所有乘客坐稳再开车

        ![函数防抖](/assets/img/函数防抖和节流/防抖.png "函数防抖")

2. lodash
    * `_.debounce`

3. 应用场景
    * 搜索框

## 二、节流(throttle)
1. 基本原理
    * `节流`指频繁触发事件时，只会在指定的时间段内执行事件回调，即触发事件间隔大于等于指定的时间才会执行回调函数
    * 生活案例解释
        - 类比到生活中的水龙头，拧紧水龙头到某种程度会发现，每隔一段时间，就会有水滴流出

        ![函数节流](/assets/img/函数防抖和节流/节流.png "函数节流")

2. lodash
    * `_.throttle`

3. 应用场景
    - 滚动事件

## 三、参考链接
* [十分钟学会防抖和节流](https://www.cnblogs.com/zhuanzhuanfe/p/10633019.html)
* [JS 防抖与节流](https://juejin.im/post/5c87b54ce51d455f7943dddb)
* [7分钟理解JS的节流、防抖及使用场景](https://juejin.im/post/5b8de829f265da43623c4261)
* [JavaScript专题系列20篇](https://juejin.im/post/59eff1fb6fb9a044ff30a942)
* [防抖和节流的应用场景和实现](https://juejin.im/post/5b9382e3e51d450e9942e0ee)


        

