---
title: TensorFlow 1.0 文档翻译计划（附文档目录）
date: 2017-02-23 18:17:46
tags: TensorFlow
category: TensorFlow
---

> 非生而知之者，当学而不辍。

## 写在前面

Google 的 [TensorFlow](https://www.tensorflow.org/) 发布 1.0 版本了。最近一直在关注 Machine Learning 这方面的东东，个人认为（就目前来说）TensorFlow 在这个领域是首先需要学习的。

[TensorFlow中文社区](http://www.tensorfly.cn)给了我很多帮助，感谢！可惜他们的文档有点久了（目前还是 0.5 版本），跟现在的 1.0 区别还是有点多。而我是直接从 1.0 开始学习的，虽然直接看官方的英文文档还算没有问题。为了督促自己持续的学习，同时加深学习的效果，所以决定开始个人翻译 TensorFlow 1.0 官方文档的计划。当然如果有其他同好愿意一起翻译的话，也非常欢迎。文档翻译项目的源码部署在 Github 上，源码 repo：https://github.com/isaron/tfdocs.git。

文档翻译过程中克隆了[官方文档库](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/g3doc)（尽量保持跟随最新更新），同时严重参考了[TensorFlow中文社区](http://www.tensorfly.cn/)的文档。

本文档项目使用[MkDocs文档系统](http://mkdocs.org)构建，界面主题为[Read the Docs](https://readthedocs.org/)。

本文档部署于[https://huangch.me/tfdocs](https://huangch.me/tfdocs)。

## 文档目录
尽量与官方网站的文档目录保持一致，已翻译完成的章节会及时更新链接
<!-- more -->
### 1. 安装

* [安装综述](https://huangch.me/tfdocs/install/install-index)
* 在Ubuntu上安装TensorFlow
* 在Mac OS X上安装TensorFlow
* 在Windows上安装TensorFlow
* 源代码安装TensorFlow
* 迁移到TensorFlow 1.0

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
* Tensor Ranks, Shapes, and Types
* Variables: Creation, Initialization, Saving, and Loading

#### 2.3 教程

* Mandelbrot Set
* Partial Differential Equations
* Convolutional Neural Networks
* Image Recognition
* How to Retrain Inception’s Final Layer for New Categories
* Vector Representations of Words
* Recurrent Neural Networks
* Sequence-to-Sequence Models
* A Guide to TF Layers: Building a Convolutional Neural Network
* Large-scale Linear Models with TensorFlow
* TensorFlow Linear Model Tutorial
* TensorFlow Wide & Deep Learning Tutorial
* Using GPUs

#### 2.4 性能优化

* Performance
* XLA Overview
* Broadcasting semantics
* Developing a new backend for XLA
* Using JIT Compilation
* Operation Semantics
* Shapes and Layout
* Using AOT compilation
* How to Quantize Neural Networks with TensorFlow

### 3. API r1.0

* Overview r1.0
* Python API r1.0
* C++ API r1.0
* Java API r1.0
* Go API

### 4. 部署

* How to run TensorFlow on Hadoop
* Distributed TensorFlow
* TensorFlow Serving

### 5. 扩展

* TensorFlow Architecture
* Adding a New Op
* Adding a Custom Filesystem Plugin
* TensorFlow in other languages
* Custom Data Readers
* Creating Estimators in tf.contrib.learn
* A Tool Developer’s Guide to TensorFlow Model Files

### 6. 资源

#### 6.1 社区

* Writing TensorFlow Documentation
* TensorFlow Style Guide

#### 6.2 关于

* Additional Resources
* TensorFlow White Papers
* TensorFlow Uses

### 7. TensorFlow版本

* TensorFlow Versions
* master
* r1.0
* r0.12
* r0.11
* r0.10
