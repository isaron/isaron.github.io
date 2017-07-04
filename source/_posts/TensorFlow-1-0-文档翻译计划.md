---
title: TensorFlow 1.0 文档翻译计划（附文档目录）
date: 2017-02-23 18:17:46
tags: TensorFlow
category: TensorFlow
top: 1
---

> 非生而知之者，当学而不辍。

## 写在前面

Google 的 [TensorFlow](https://www.tensorflow.org/) 发布 1.0 版本了。最近一直在关注 Machine Learning 这方面的东东，个人认为（就目前来说）TensorFlow 在这个领域是首先需要学习的。

[TensorFlow中文社区](http://www.tensorfly.cn)给了我很多帮助，感谢！可惜他们的文档有点久了（目前还是 0.5 版本），跟现在的 1.0 区别还是有点多。而我是直接从 1.0 开始学习的，虽然直接看官方的英文文档还算没有问题，但为了督促自己持续的学习，同时加深学习的效果，所以决定开始个人翻译 TensorFlow 1.0 官方文档的计划。当然如果有其他同好愿意一起翻译的话，也非常欢迎。文档翻译项目的源码部署在 Github 上，源码 repo：https://github.com/isaron/tfdocs.git。

文档翻译过程中克隆了[官方文档库](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/g3doc)（尽量保持跟随最新更新），同时严重参考了[TensorFlow中文社区](http://www.tensorfly.cn/)的文档。

本文档项目使用[MkDocs文档系统](http://mkdocs.org)构建，界面主题为[Read the Docs](https://readthedocs.org/)。

本文档部署于[https://huangch.me/tfdocs](https://huangch.me/tfdocs)。

## 文档目录
尽量与官方网站的文档目录保持一致，已翻译完成的章节会及时更新链接
<!-- more -->
### 1. 安装

* [安装综述](https://huangch.me/tfdocs/install)
* [在Ubuntu上安装TensorFlow](https://huangch.me/tfdocs/install/install_linux)
* [在Mac OS X上安装TensorFlow](https://huangch.me/tfdocs/install/install_mac)
* [在Windows上安装TensorFlow](https://huangch.me/tfdocs/install/install_windows)
* [源代码安装TensorFlow](https://huangch.me/tfdocs/install/install_sources)
* [迁移到TensorFlow 1.0](https://huangch.me/tfdocs/install/migration)
* [安装TensorFlow for Java](https://huangch.me/tfdocs/install/install_java)
* [安装TensorFlow for C](https://huangch.me/tfdocs/install/install_c)
* [安装TensorFlow for Go](https://huangch.me/tfdocs/install/install_go)

### 2. 开发

#### 2.1 新手入门

* TensorFlow快速入门
* MNIST入门
* MNIST进阶
* TensorFlow 运作方式 101
* tf.contrib.learn: 快速开始
* tf.contrib.learn: 创建输入函数
* TensorBoard: 可视化学习
* TensorBoard: 内嵌可视化
* TensorBoard: 图表可视化
* tf.contrib.learn: 日志和监控基础
* TensorFlow版本

#### 2.2 程序员手册

* 读取数据
* 线程和队列
* 共享参数
* TensorFlow的版本语义
* TensorFlow数据版本化: GraphDefs and Checkpoints
* Supervisor: Training Helper for Days-Long Trainings.
* TensorFlow Debugger (tfdbg) 命令行指南: MNIST
* TensorFlow Debugger (tfdbg) 与 tf.contrib.learn 结合使用
* 导入导出MetaGraph
* 常见问题
* Tensor 排名、形状和类型
* 变量：创建、初始化、保存和加载

#### 2.3 教程

* 曼德布洛特(Mandelbrot)集合
* 偏微分方程(PDEs)
* 卷积神经网络
* 图像识别
* 如何训练 Inception’s Final Layer for New Categories
* 字词的向量表示
* 递归神经网络
* Sequence-to-Sequence 模型
* TF Layers 指南: 创建卷积神经网络
* 大规模线性模型与 TensorFlow
* TensorFlow 线性模型指导
* TensorFlow 广度与深度学习指导
* 使用 GPU

#### 2.4 性能优化

* 总览
* XLA 概览
* 广播语义
* 开发新的 XLA 后端
* 使用 JIT 编译
* 运算语义
* Shapes and Layout
* 使用 AOT 编译
* 如何量化神经网络

### 3. API r1.0

* 概览 r1.0
* Python API r1.0
* C++ API r1.0
* Java API r1.0
* Go API

### 4. 部署

* 在 Hadoop 上运行 TensorFlow
* 分布式部署 TensorFlow
* TensorFlow 服务

### 5. 扩展

* TensorFlow 架构
* 添加新的 Op
* 添加自定义文件系统插件
* TensorFlow 翻译
* 自定义数据读取
* 用 tf.contrib.learn 建立估量
* TensorFlow 模型文件的工具开发者指南

### 6. 资源

#### 6.1 社区

* 编写 TensorFlow 文档
* TensorFlow 风格指南

#### 6.2 关于

* 更多TF相关资源
* TensorFlow 白皮书
* TensorFlow Uses

### 7. TensorFlow版本

* TensorFlow 版本列表
* master
* r1.0
* r0.12
* r0.11
* r0.10

## 内容来源

英文官方网站：
    https://www.tensorflow.org/

TensorFlow中文社区:
    http://www.tensorfly.cn

极客学院TensorFlow文档中文版翻译计划：
    https://github.com/jikexueyuanwiki/tensorflow-zh
