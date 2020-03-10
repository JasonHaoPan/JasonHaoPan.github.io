---
title: Set up Intellij for work environment 
date: 2020-01-01T18:15:53+00:00
author: panhao
layout: post
categories:
  - 总结
  - 工作
  - work
tags:
  - 总结
  - 工作
  - work
---

   公司使用**Eclipse**很多年了，但是为了让开发更便捷省时，还是决定转向IntelliJ。购买一年的**Intellij**可以获得当前的perpetual fallback license其实还是比较划算的。
公司的整体项目是使用gitlab作为版本控制工具的，只需要在**IntelliJ**中导入git项目即可。
需要注意的是**Intellij**的项目架构和Eclipse有些不同，**Intellij**以project为单位可以分为不同的module。
公司的项目架构，以jsp，js，java为主，不同的版本分为不同的module导入即可。

   导入后设置模块的SDK和library以及编译输入路径。需要注意的是在编译项目时曾经遇到过内存不足的问题，需要设置compiler的内存容量。
设置完成后配置tomcat。在deployment中选择需要部署的项目架构即可，对于不同的artifact/module可以部署到不同路径。
完成后即可编译，启动服务。
对于插件的使用，以后会再做补充。

   使用Intellij能明显感受到查找时间的缩短和编译时间的减少，配合各种shortcut确实方便许多。