# 18-19-object-detection-papers
18-19目标检测论文汇总  
1. [SIN] Structure Inference Net: Object Detection Using Scene-Level Context and Instance-Level Relationships，CVPR2018  
简介：利用场景和实例推理，提高识别正确率  
[解读](https://blog.csdn.net/joyeuxni/article/details/81151969) [github地址](https://github.com/choasup/SIN)  

2. [STDN] Scale-Transferrable Object Detection，CVPR2018  
简介：Densenet169+尺度变换模块+ssd框架，提高小物体识别率  
[解读](https://blog.csdn.net/xh_hit/article/details/79512146) [github地址](https://github.com/arvention/STDN-PyTorch)

3. [RefineDet] Single-Shot Refinement Neural Network for Object Detection，CVPR2018
简介：将Faster RCNN和SSD结合  
[解读](https://blog.csdn.net/qq_21949357/article/details/80642551) [github地址](https://github.com/sfzhang15/RefineDet)

4. [MegDet] MegDet: A Large Mini-Batch Object Detector，CVPR2018  
简介：从大Mini-Batch的运用 和Batch Normalizatio（BN）的训练技巧出发，在训练方法上实现优化  
[解读](https://blog.csdn.net/Julialove102123/article/details/80471403)

5. [DA Faster R-CNN] Domain Adaptive Faster R-CNN for Object Detection in the Wild，，CVPR2018
简介：基于Faster-RCNN，进行领域自适应改进（似迁移学习），用在进行雾气，光线不良情况下的野外迁移探测活动（复杂多变的场景）  
[解读](https://blog.csdn.net/qq_18882399/article/details/81188573) [github地址](https://github.com/yuhuayc/da-faster-rcnn)

6. [SNIP] An Analysis of Scale Invariance in Object Detection，CVPR2018  
简介：图像金字塔上检测相同大小，保留尺寸在指定范围之内的输出结果，解决尺度不变性问题  
[解读](https://zhuanlan.zhihu.com/p/36431183)

7. [Relation-Network] Relation Networks for Object Detection，CVPR2018  
简介：基于Faster RCNN系列算法引入object relation module来刻画物体之间的关系，来取代nms进行去重，且提升检测效果。  
[解读](https://www.jianshu.com/p/8ee6884bbd68) [github地址](https://github.com/msracver/Relation-Networks-for-Object-Detection)

8. [Cascade R-CNN] Cascade R-CNN: Delving into High Quality Object Detection，CVPR2018  
简介：级联的RCNN，使用多个IoU threshold递增的header，每一级使用上一级refine过后的bbox作为输入。这样可以保证每一级的header都可以得到足够多的正样本，且正样本的质量可以逐级提升。  
[解读](https://blog.csdn.net/wfei101/article/details/80024406) [github地址](https://github.com/zhaoweicai/cascade-rcnn)

9. [MLKP] Multi-scale Location-aware Kernel Representation for Object Detection，CVPR2018  
简介：基于Faster-RCNN,不同卷积块中的多层特征，将它们连接成一个单一的特征图，然后计算这些特征图上的高阶统计量。引入了一个可训练的位置权重结构来评估不同位置的贡献，使我们的表示位置更加敏感。最后，将不同的表示顺序连接起来进行分类和回归。检测器更具辨别力，对小目标和遮挡物体检测提升效果显著。  
[解读](http://www.pianshen.com/article/7806238840/) [github地址](https://github.com/Hwang64/MLKP)

10. [Fitness NMS] Improving Object Localization with Fitness NMS and Bounded IoU Loss，CVPR2018  

11. [STDnet] STDnet: A ConvNet for Small Target Detection，BMVC2018  

12. [RFBNet] Receptive Field Block Net for Accurate and Fast Object Detection，ECCV' 18  
简介：基于SSD，在Inception的基础上加入了dilated膨胀卷积，增大了感受野，在保证速度的情况下，增加了检测精度。  
[解读](https://blog.csdn.net/u014380165/article/details/81556769) [github地址](https://github.com/ruinmessi/RFBNet)

13. [CornerNet] CornerNet: Detecting Objects as Paired Keypoints，ECCV' 18  
简介：one-stage，通过将目标检测变为为成对关键点，达到anchor-free，引入了corner pooling，更好定位角点。  
[解读](https://blog.csdn.net/weixin_40414267/article/details/82379793) [github地址](https://github.com/princeton-vl/CornerNet)

14. [PFPNet] Parallel Feature Pyramid Network for Object Detection，ECCV' 18  
简介：one stage，借鉴了SPP的思想并通过MSCA特征融合，多尺度多特征图融合检测。  
[解读](https://blog.csdn.net/duanyajun987/article/details/82590166)

15. [Softer-NMS] Softer-NMS: Rethinking Bounding Box Regression for Accurate Object Detection，ECCV' 18  
[github地址](https://github.com/yihui-he/softer-NMS)

16. [ShapeShifter] ShapeShifter: Robust Physical Adversarial Attack on Faster R-CNN Object Detector，ECML-PKDD-2018  
[github地址](https://github.com/shangtse/robust-physical-attack)

17. [Pelee] Pelee: A Real-Time Object Detection System on Mobile Devices，NIPS' 18  
简介：DesNet的变种版本PeleeNet，适用于移动端的轻量级网络。
[github地址](https://github.com/Robert-JunWang/Pelee)

18. [HKRM] Hybrid Knowledge Routed Modules for Large-scale Object Detection，NIPS' 18  

19. [MetaAnchor] MetaAnchor: Learning to Detect Objects with Customized Anchors，NIPS' 18  

20. [SNIPER] SNIPER: Efficient Multi-Scale Training，NIPS' 18  
[github地址](https://github.com/mahyarnajibi/SNIPER)

21. [M2Det] M2Det: A Single-Shot Object Detector based on Multi-Level Feature Pyramid Network，AAAI2019  
简介：主干网络中两个不同尺寸的特征图，进行多级U型网络得到Multi-level&Mutli-scale特征图，多级同尺寸的特征图融合，得到6个不同scale的多级特征金字塔，进行回归与分类。  
[解读](https://blog.csdn.net/sinat_37532065/article/details/87385302) [github地址](https://github.com/qijiezhao/M2Det)  

22. [R-DAD] Object Detection based on Region Decomposition and Assembly，AAAI2019  
简介：针对two-stage检测框架的region proposal，把proprsal上下、左右分解后进行融合，从region proposal的阶段改善对部分遮挡物体的检测。  
[解读](https://blog.csdn.net/qq_30708445/article/details/88182603)

23. [GIoU] Generalized Intersection over Union: A Metric and A Loss for Bounding Box Regression，CVPR2019  
简介：提出用IoU这个直接的指标来指导回归任务的学习，用直接指标IoU作为损失函数的缺陷性，提出新的metric来代替L1、L2损失函数，从而提升regression效果  
[解读](https://mp.weixin.qq.com/s?__biz=MzI5MDUyMDIxNA==&mid=2247487503&idx=1&sn=e98437efda298a9d8fe1a386c5a96601&chksm=ec1ffdf6db6874e03e1e05d438ebd0d295364d01ca8b2741bdad8ffa5d328032ad24ae76a289&token=762499696&lang=zh_CN&scene=21#wechat_redirect)  

24. Automatic adaptation of object detectors to new domains using self-training，CVPR2019  

25. [Libra R-CNN] Libra R-CNN: Balanced Learning for Object Detection，CVPR2019  
简介：针对训练过程中的采样不平衡（简单负样本过多）、特征层不平衡（非相邻层级的语义信息变得稀释）、任务不平衡（分类与定位）进行改进。  
[解读](https://www.cnblogs.com/fourmi/p/10756556.html) [github地址](https://github.com/OceanPang/Libra_R-CNN)

26. [FSAF] Feature Selective Anchor-Free Module for Single-Shot Object Detection  
简介：RetinaNet+FSAF模块让每个instance自动的选择最合适的feature_map，选择的依据有原来的instance size变成了instance content。实现方法：anchor-free模块计算instance在所有feature_map进行预测后的损失，选择loss最小的作为该instance最佳的feature_map，并用anchor_based进行预测，提高检测精度。  
[解读](https://mp.weixin.qq.com/s?__biz=MzI5MDUyMDIxNA==&mid=2247487638&idx=2&sn=1e9f26013b3d9ab4fd4137729894606a&chksm=ec1ffd6fdb687479183be59ec102f28bff4a5521903707fef744449e7630252c5298b66f339b&token=1948754723&lang=zh_CN&scene=21#wechat_redirect)  

27. [ExtremeNet] Bottom-up Object Detection by Grouping Extreme and Center Points，CVPR2019  
简介：Hourglass网络作为backbone，按照CornerNet的结构和损失函数，预测四个extreme point（顶、左、底、右）以及目标的中心点，完成检测。  
[解读](https://www.cnblogs.com/cieusy/p/10399960.html) [github地址](https://github.com/xingyizhou/ExtremeNet)

28. [C-MIL] Continuation Multiple Instance Learning for Weakly Supervised Object Detection，CVPR2019  
[github地址](https://github.com/AnonymousIDs/C-MIL)

29. [ScratchDet] Training Single-Shot Object Detectors from Scratch，CVPR2019  
简介：从优化的角度出发，通过实验解释了梯度稳定手段之一的 BatchNorm 是如何帮助随机初始化训练一阶段检测器 SSD，进而结合了 ResNet 与 VGGNet 来加强对小物体的检测。  
[解读](https://mp.weixin.qq.com/s/TZj0QzDXE6QbCY5-pT6RNQ) [github地址](https://github.com/KimSoybean/ScratchDet)

30. Bounding Box Regression with Uncertainty for Accurate Object Detection，CVPR2019  
简介：提出了一中新的边界框回归损失算法，提高了各种检测体系的目标定位精度  
[github地址](https://github.com/yihui-he/KL-Loss)

31. Activity Driven Weakly Supervised Object Detection，CVPR2019    
[github地址](https://github.com/zhenheny/ADWSOD)

32. Towards Accurate One-Stage Object Detection with AP-Loss，CVPR2019    
简介：提出一种新的训练框架，排序任务替换一阶目标检测器中的分类任务，AP来作为损失函数

33. Strong-Weak Distribution Alignment for Adaptive Object Detection，CVPR2019    
[github地址](https://github.com/VisionLearningGroup/DA_Detection)

34. [NAS-FPN] Learning Scalable Feature Pyramid Architecture for Object Detection，CVPR2019  
简介：使用神经架构搜索（NAS）框架为RetinaNet框架发现更好的 FPN 架构。

35. Towards Universal Object Detection by Domain Attention，CVPR2019  

36. Exploring the Bounds of the Utility of Context for Object Detection，CVPR2019  

37. Dissimilarity Coefficient based Weakly Supervised Object Detection，CVPR2019  

38. [GA-RPN] Region Proposal by Guided Anchoring，CVPR2019    
简介：通过FPN预测 anchor 的位置和形状，生成稀疏而且形状任意的 anchor，并且设计Feature Adaption 模块来修正特征图使之与 anchor精确匹配  
[解读](https://mp.weixin.qq.com/s/Sl958JkcJjy-HW9_c-SH4g) [github地址](https://github.com/open-mmlab/mmdetection)

39. A Simple Pooling-Based Design for Real-Time Salient Object Detection，CVPR2019    
[解读](https://blog.csdn.net/ruoruojiaojiao/article/details/89519806) [github地址](https://github.com/backseason/PoolNet)

40. [TridentNet] Scale-Aware Trident Networks for Object Detection，CVPR2019    
[解读](https://zhuanlan.zhihu.com/p/54334986) [github地址](https://github.com/TuSimple/simpledet/tree/master/models/tridentnet)

