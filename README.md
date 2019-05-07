# 18-19-object-detection-papers
18-19目标检测论文汇总  

21. [M2Det] M2Det: A Single-Shot Object Detector based on Multi-Level Feature Pyramid Network，AAAI2019
[github地址](https://github.com/qijiezhao/M2Det)  

22. [R-DAD] Object Detection based on Region Decomposition and Assembly，AAAI2019  

23. [GIoU] Generalized Intersection over Union: A Metric and A Loss for Bounding Box Regression，CVPR2019  
简介：提出用IoU这个直接的指标来指导回归任务的学习，用直接指标IoU作为损失函数的缺陷性，提出新的metric来代替L1、L2损失函数，从而提升regression效果  
[解读](https://mp.weixin.qq.com/s?__biz=MzI5MDUyMDIxNA==&mid=2247487503&idx=1&sn=e98437efda298a9d8fe1a386c5a96601&chksm=ec1ffdf6db6874e03e1e05d438ebd0d295364d01ca8b2741bdad8ffa5d328032ad24ae76a289&token=762499696&lang=zh_CN&scene=21#wechat_redirect)  

24. Automatic adaptation of object detectors to new domains using self-training，CVPR2019

25. [Libra R-CNN] Libra R-CNN: Balanced Learning for Object Detection，CVPR2019

26. [FSAF] Feature Selective Anchor-Free Module for Single-Shot Object Detection
简介：RetinaNet+FSAF模块让每个instance自动的选择最合适的feature_map，选择的依据有原来的instance size变成了instance content
[解读](https://mp.weixin.qq.com/s?__biz=MzI5MDUyMDIxNA==&mid=2247487638&idx=2&sn=1e9f26013b3d9ab4fd4137729894606a&chksm=ec1ffd6fdb687479183be59ec102f28bff4a5521903707fef744449e7630252c5298b66f339b&token=1948754723&lang=zh_CN&scene=21#wechat_redirect)

27. [ExtremeNet] Bottom-up Object Detection by Grouping Extreme and Center Points，CVPR2019
[github地址](https://github.com/xingyizhou/ExtremeNet)

28. [C-MIL] Continuation Multiple Instance Learning for Weakly Supervised Object Detection，CVPR2019
[github地址](https://github.com/AnonymousIDs/C-MIL)

29. [ScratchDet] Training Single-Shot Object Detectors from Scratch，CVPR2019
简介：从优化的角度出发，通过实验解释了梯度稳定手段之一的 BatchNorm 是如何帮助随机初始化训练一阶段检测器 SSD，进而结合了 ResNet 与 VGGNet 来加强对小物体的检测。
[解读](https://mp.weixin.qq.com/s/TZj0QzDXE6QbCY5-pT6RNQ) [github地址](https://github.com/KimSoybean/ScratchDet)

30. Bounding Box Regression with Uncertainty for Accurate Object Detection，CVPR2019
简介：提出了一中新的边界框回归损失算法，提高了各种检测体系的目标定位精度
[github地址](https://github.com/yihui-he/KL-Loss)

31. Activity Driven Weakly Supervised Object Detection
[github地址](https://github.com/zhenheny/ADWSOD)

32. Towards Accurate One-Stage Object Detection with AP-Loss
简介：提出一种新的训练框架，排序任务替换一阶目标检测器中的分类任务，AP来作为损失函数

33. Strong-Weak Distribution Alignment for Adaptive Object Detection
[github地址](https://github.com/VisionLearningGroup/DA_Detection)

34. [NAS-FPN] Learning Scalable Feature Pyramid Architecture for Object Detection

35. Towards Universal Object Detection by Domain Attention

36. Exploring the Bounds of the Utility of Context for Object Detection

37. Dissimilarity Coefficient based Weakly Supervised Object Detection

38. [GA-RPN] Region Proposal by Guided Anchoring
简介：通过FPN预测 anchor 的位置和形状，生成稀疏而且形状任意的 anchor，并且设计Feature Adaption 模块来修正特征图使之与 anchor精确匹配
[解读](https://mp.weixin.qq.com/s/Sl958JkcJjy-HW9_c-SH4g) [github地址](https://github.com/open-mmlab/mmdetection)

39. A Simple Pooling-Based Design for Real-Time Salient Object Detection
[github地址](https://github.com/backseason/PoolNet)

40. [TridentNet] Scale-Aware Trident Networks for Object Detection
[解读](https://zhuanlan.zhihu.com/p/54334986) [github地址](https://github.com/TuSimple/simpledet/tree/master/models/tridentnet)

