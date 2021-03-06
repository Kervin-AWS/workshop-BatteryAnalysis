---
title: "Overview"
date: 2018-10-03T10:17:52-07:00
draft: false
weight: 10
---

如何准确的根据电池放电过程中的相关信息，预测出电池的剩余寿命，是一个具有实际生产价值的问题。

本实验基于公开的[锂电池数据集](https://www.onacademic.com/detail/journal_1000042285447899_143a.html)，该数据集收录了**124枚电池（APR18650M1A）**，从出厂到生命终结（电池满电容量为正常值的80%）过程中电流、温度、等关键指标。本实验将基于以上数据，进行锂电池的**剩余寿命的预测研究**。

本实验的**目标**是训练一个可以根据**20轮**充放电的电池监控历史数据，预测该电池的剩余充电寿命的神经网络，本实验的神经网络架构主要运用 [LSTM 和CNN 的融合框架](https://github.com/dsr-18/long-live-the-battery)。

本实验将从SageMaker NoteBook创建开始介绍，并引导您基于SageMaker实现：

- 电池数据导入

- 数据概览

- 数据预处理

- 模型训练

- 模型预测
