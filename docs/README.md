
<center>
<h1>Koishi 开发入门教程


</center>

# 介绍

> 本文档旨在介绍一些入门基础的操作方法
> 
> 帮助你快速上手一些开发项目的实践

---


> ## 点击这里 [观看koishi官方（孤梦星影）的视频教程](https://www.bilibili.com/video/BV1pW4y1V7qV?spm_id_from=333.788.videopod.sections&vd_source=4244b3f29cfb50629be564a84f17d2f1)


## Koishi优点
 Koishi机器人框架有什么优点呢
- 开箱即用
使用桌面安装包安装后即可使用
- 生态丰富
截至目前（2024-11-20）已有1920+的机器人插件
- 专为开发者打造
类型支持：Koishi 完全基于 TypeScript 开发，拥有顶级的类型支持
- 模块热重载：开发 Koishi 插件时，只需轻点保存即可热重载，无需频繁重启机器人，如同前端开发一样丝滑顺畅
- 等等

---

>（下面是alin的教程）
## 本教程会简单介绍：

 - #### [nodejs安装](p1/p1.md)
 - #### [python安装](p1/p6.md)
 - #### [vscode安装,这里引用下这个教程，讲的很详细了](https://cloud.tencent.com/developer/article/2119156)
 - #### [koishi模板项目创建](p1/p2.md)
 - #### [插件创建](p1/p4.md)
 - #### [插件编写基础教程](p1/p7.md)
 - #### [js基础语法](p1/p5.md)
 - #### [简单的数据库使用](p1/p9.md)
 - #### [简单的api调用](p1/p10.md)
 - #### [简单的图片渲染](p1/p11.md)
 - #### [插件编写基础-进阶教程](p1/p12.md)
 - #### 配置文件
 - #### 发布插件
 - #### alin的异地开发方法

!> **需要注意，本教程暂时只针对Windows平台**

!> **免责声明：本教程仅供参考，内容为作者个人的使用习惯，不代表唯一方法，也不是绝对正确的方法，其内容旨在提供一般性指导。实际结果可能因个人情况而异。我们不对因使用本教程所产生的任何损失或损害承担责任。请根据最新信息自行判断和应用。感谢您的理解与支持。**


!> **教程使用和传播说明：本教程供个人学习和参考使用。在尊重我们的版权的前提下，可以自由分享和传播。请勿将此教程用于任何商业目的，亦不要进行任何形式的修改以误导他人。感谢您的支持与合作。**

**那么，开始吧~😽😽**

---

### 创建模板项目

开发koishi首先最重要的就是先创建个koishi模板项目啦

* 如果是在一台全新电脑（或虚拟机）开发，那需要修复下DirectX图形API，[请先看这里哦](p1/p1.1.md) 

* 如果是在您的主力机开发，且从来没有开发过什么东西，[请看这里哦](p1/p1.md) 

* 如果您已经开发过或创建过koishi的模板项目，呜哇，那可以跳转到[这里](p1/p2.md)
  

