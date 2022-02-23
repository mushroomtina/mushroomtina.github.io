---
title: blog1
date: 2022-02-22 22:47:40
tags:
---

# leetcode刷题笔记

## 二分查找

如果 nums[mid] < target ，由于数组有序，mid 以及 mid 左边的所有元素都小于 target，目标元素一定在区间 [mid + 1, right] 里，因此设置 left = mid + 1。

### ref： https://ojeveryday.github.io/AlgoWiki/#/BinarySearch/README?id=%e4%ba%8c%e5%88%86%e6%9f%a5%e6%89%be%e6%a8%a1%e6%9d%bf%e4%b8%80

