---
title: 使用js移位运算符取整
date: 2022-09-28 16:23:20
tags:
- 日常记录
categrories:
- JavaScript
---

使用js移位运算符取整

# 运算符介绍

## 有符号右移
`>>`该操作符会将指定操作数的二进制位向右移动指定的位数。<b>向右被移出的位被丢弃，拷贝最左侧的位以填充左侧。</b>由于新的最左侧的位总是和以前相同，符号位没有被改变。

## 无符号右移
`>>>`该操作符会将第1个操作数向右移动指定的位数。<b>向右被移出的位被丢弃，左侧用0填充。</b>因为符号位变成了0，所以结果总是非负的.

# 妙用

## 用于取整
```
console.log(3.14 >> 0)  // 3
console.log(3.14 >>> 0)  // 3 (不可对负数取整)
```

## 用于获取除2之后的整数
```
console.log(5 >> 1)  // 2
console.log(4 >> 1)  // 2
```