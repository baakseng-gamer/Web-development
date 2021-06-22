# 航公JS思维导图

目录
- [航公JS思维导图](#航公js思维导图)
- [第一篇 常用方法](#第一篇-常用方法)
  - [01.JS基础知识](#01js基础知识)
  - [02.三类输出方式](#02三类输出方式)
  - [03.Number 数据类型](#03number-数据类型)
  - [04.String 数据类型](#04string-数据类型)
  - [05.Boolean 数据类型](#05boolean-数据类型)
  - [06.Object 数据类型](#06object-数据类型)
  - [07.条件判断里的相互转换规则](#07条件判断里的相互转换规则)
  - [09.JS中三种常见的判断](#09js中三种常见的判断)
  - [08.数据类型之间的区别](#08数据类型之间的区别)
  - [10.JS中的for循环](#10js中的for循环)
  - [11.函数基础知识（全）](#11函数基础知识全)
  - [12.数组的基础知识](#12数组的基础知识)
  - [13.数组中常用的方法](#13数组中常用的方法)
  - [14.数组中常用的方法补充](#14数组中常用的方法补充)
  - [15.Math的常用方法](#15math的常用方法)
  - [16.字符串的常用方法](#16字符串的常用方法)
- [第二篇 常用方法（实用的）](#第二篇-常用方法实用的)
  - [1.数组去重的三种方法](#1数组去重的三种方法)
  - [2.时间格式化的三种方法](#2时间格式化的三种方法)
  - [3.URL参数处理的三种方法](#3url参数处理的三种方法)
  - [4.获取随机验证码](#4获取随机验证码)
  - [5.获取DOM标签的方式](#5获取dom标签的方式)
  - [6.获取DOM节点的方式](#6获取dom节点的方式)
  - [7.DOM元素的增加/删除/修改](#7dom元素的增加删除修改)
  - [8.操作DOM元素样式](#8操作dom元素样式)


***


# 第一篇 常用方法

## 01.JS基础知识

JS组成的三个部分, JS中的变量, JS中的数据类型

https://web.mindyushu.com/s/gsp

## 02.三类输出方式

console, window提示框, 页面插入

https://web.mindyushu.com/s/gcf

## 03.Number 数据类型

包含, isNaN, 其他类型转换为数字类型, 扩展

https://web.mindyushu.com/s/i4q

## 04.String 数据类型

定义, 其他类型转字符串类型, 字符串的数学运算

https://web.mindyushu.com/s/fg1

## 05.Boolean 数据类型

包含, 其他类型转布尔类型

https://web.mindyushu.com/s/2Vd

## 06.Object 数据类型

特点, 键值对, 引用数据类型不能作为属性名, 数组

https://web.mindyushu.com/s/iOR

## 07.条件判断里的相互转换规则

数字 == 字符串, 数字 == 布尔, 字符串 == 布尔, 对象 == 数字, 对象 == 字符串, 对象 == 布尔, 对象 == 对象, 规律, 特殊

https://web.mindyushu.com/s/5E4

## 09.JS中三种常见的判断

if...else if...else, 三元运算符, switch...case, 相关的散知识

https://web.mindyushu.com/s/Ro

## 08.数据类型之间的区别

webkit底层运行机制, 基本数据类型（值类型）, 引用数据类型（对象函数）

https://web.mindyushu.com/s/m9i

## 10.JS中的for循环

for循环, for...in循环, 循环中的关键字, a++、a+=1、a=a+1的区别

https://web.mindyushu.com/s/hjX

## 11.函数基础知识（全）

定义, 作用, 目的, 函数的两部分

https://web.mindyushu.com/s/n83

## 12.数组的基础知识

定义, 特性, 了解, 学习重点, 使用

https://web.mindyushu.com/s/6l3

## 13.数组中常用的方法

1.增删改, 2.查询和拼接, 3.把数组转换成字符串, 4.检测数组中是否包含某一项, 5.排序或者排列, 6.遍历及映射, 7.其他方法

https://web.mindyushu.com/s/ieV

## 14.数组中常用的方法补充

reduce
, filter, flat, find 与 findIndex, some 与 every

https://web.mindyushu.com/s/gdm

## 15.Math的常用方法

1.定义, 方法

https://web.mindyushu.com/s/8kJ

## 16.字符串的常用方法

字符串与数组的区别, 1.字符查找, 2.字符截取, 3.检测是否包含某项, 4.大小写转换, 5.字符串转数组, 6.字符替换, 7.其他

https://web.mindyushu.com/s/91z



# 第二篇 常用方法（实用的）

## 1.数组去重的三种方法

双FOR循环, 对象的键值对方式, indexOf 方式

https://web.mindyushu.com/s/6EX

## 2.时间格式化的三种方法

正则处理（优）, 字符串截取（良）, replace（差）

https://web.mindyushu.com/s/4LA

## 3.URL参数处理的三种方法

字符串处理, A标签处理, 正则处理

https://web.mindyushu.com/s/9DA

## 4.获取随机验证码

需求, 不考虑重复, 考虑重复

https://web.mindyushu.com/s/2LyE

## 5.获取DOM标签的方式

document.getElementById([ID]), [context].getElementByTagName([标签名]), [context].getElementByClassName([样式类])
, [context].getElementByName([NAME 属性名]), document.documentElement, document.body, document.head, ---------------------------上面一个，下面一个----------------------------------------, [context].querySelectorAll([选择器]), 在不考虑兼容的情况下，这两种方法足以我们需要的元素对象和集合了

https://web.mindyushu.com/s/dRR

## 6.获取DOM节点的方式

所有页面中所呈现的内容，都是DOM文档中的一个节点（node）, document.getElementById([ID]), 节点类型, ---------------------------------------------------华丽的分割线--------------------------------------------------------------, 属性

https://web.mindyushu.com/s/m4r

## 7.DOM元素的增加/删除/修改

创建, 增加, 删除, 设置自定义属性, 给DOM设置内容

https://web.mindyushu.com/s/dbb

## 8.操作DOM元素样式

元素.style.xxx, 元素.className

https://web.mindyushu.com/s/kSN