---
title: Spack简明教程
author: Jianfeng
date: '2019-02-27'
slug: spack-tutorial
categories:
  - tutorial
tags:
  - package management
---

## 简介

[Spack](https://spack.io/)是一种主要针对超级计算机（High Performance Computing，HPC）运行环境开发的科学软件包管理器。如果你之前使用过[conda](https://www.anaconda.com/)，那么我非常推荐你在你的HPC环境上同时使用Spack工具，特别是针对某些运行时（runtime）不符合你预期的conda预编译程序。

目前可以运行在Linux和macOS操作系统的软件包管理器。它使安装科学软件变得容易。使用Spack可以构建具有多个版本，配置，平台和编译器的软件包，并且所有这些构建可以在同一台计算机上共存。

Spack与特定语言无关; 您可以使用Python 或R 构建软件堆栈 ，链接到用C，C ++或Fortran编写的库，并轻松 交换编译器。使用Spack安装在主目录中， 管理群集上的共享安装和模块，或构建组合版本的软件以进行测试。
