# 18-19-object-detection-papers
18-19目标检测论文汇总
21. [M2Det] M2Det: A Single-Shot Object Detector based on Multi-Level Feature Pyramid Network，AAAI2019
[github地址](https://github.com/qijiezhao/M2Det)

22. [R-DAD] Object Detection based on Region Decomposition and Assembly，AAAI2019

23. [GIoU] Generalized Intersection over Union: A Metric and A Loss for Bounding Box Regression，CVPR2019
简介：提出用IoU这个直接的指标来指导回归任务的学习，用直接指标IoU作为损失函数的缺陷性，提出新的metric来代替L1、L2损失函数，从而提升regression效果
解读：https://mp.weixin.qq.com/s?__biz=MzI5MDUyMDIxNA==&mid=2247487503&idx=1&sn=e98437efda298a9d8fe1a386c5a96601&chksm=ec1ffdf6db6874e03e1e05d438ebd0d295364d01ca8b2741bdad8ffa5d328032ad24ae76a289&token=762499696&lang=zh_CN&scene=21#wechat_redirect

24. Automatic adaptation of object detectors to new domains using self-training，CVPR2019

25. [Libra R-CNN] Libra R-CNN: Balanced Learning for Object Detection，CVPR2019

26. [FSAF] Feature Selective Anchor-Free Module for Single-Shot Object Detection
简介：RetinaNet+FSAF模块让每个instance自动的选择最合适的feature_map，选择的依据有原来的instance size变成了instance content

27. [ExtremeNet] Bottom-up Object Detection by Grouping Extreme and Center Points，CVPR2019
github地址：https://github.com/xingyizhou/ExtremeNet

28. [C-MIL] Continuation Multiple Instance Learning for Weakly Supervised Object Detection，CVPR2019
github地址：https://github.com/AnonymousIDs/C-MIL

29. [ScratchDet] Training Single-Shot Object Detectors from Scratch
简介：从优化的角度出发，通过实验解释了梯度稳定手段之一的 BatchNorm 是如何帮助随机初始化训练一阶段检测器 SSD，进而结合了 ResNet 与 VGGNet 来加强对小物体的检测。
