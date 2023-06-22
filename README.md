## Awesome-Multi-Sensor-Fusion

本仓库由[公众号【自动驾驶之心】](https://mp.weixin.qq.com/s?__biz=Mzg2NzUxNTU1OA==&mid=2247542481&idx=1&sn=c6d8609491a128233c3c3b91d68d22a6&chksm=ceb80b18f9cf820e789efd75947633aec9d2f1e8b58c29e5051c05a64b21ae63c244d54886a1&token=11182364&lang=zh_CN#rd) 团队整理，欢迎关注，一览最前沿的技术分享！

自动驾驶之心是国内首个自动驾驶开发者社区！这里有最全面有效的自动驾驶与AI学习路线（感知/定位/融合）和自动驾驶与AI公司内推机会！

[[Awesome Sensor Fusion]](https://github.com/stanleyw-tw/awesome-sensor-fusion)

## 一、**综述** | Overview

### 1.**近几年综述汇总** | Aggregate

Multi-modal Sensor Fusion for Auto Driving Perception: A Survey

### 2.**自动驾驶中的多传感器融合综述** | Multi-sensor fusion overview

Multi-Sensor Fusion in Automated Driving: A Survey

### 3.Multi-modal 3D Object Detection in Autonomous Driving: A Survey and Taxonomy 2023.4

Multi-modal 3D Object Detection in Autonomous Driving: A Survey and Taxonomy

### 4.Camera-Radar Perception for Autonomous Vehicles and ADAS: Concepts, Datasets and Metrics 2023.3

Camera-Radar Perception for Autonomous Vehicles and ADAS: Concepts, Datasets and Metrics

## 二、**强融合** | Strong integration

### 1.**数据级融合** | Data-level convergence

Frustum ConvNet: Sliding Frustums to Aggregate Local Point-Wise Features for Amodal 3D Object Detection

[[Code]](https://github.com/zhixinwang/frustum-convnet)

Frustum PointNets for 3D Object Detection from RGB-D Data

[[Code]](https://github.com/charlesq34/frustum-pointnets)

RoarNet: A Robust 3D Object Detection based on RegiOn Approximation Refinement

[[Code]](https://github.com/collector-m/RoarNet)

PointPainting: Sequential Fusion for 3D Object Detection

[[Code]](https://github.com/Song-Jingyu/PointPainting)

### 2.**特征级融合** | **Feature-level fusion**

#### Classic Method

MVX-Net: Multimodal VoxelNet for 3D Object Detection

Contfuse: Deep Continuous Fusion for Multi-Sensor 3D Object Detection

[[Code]](https://github.com/JaHorL/Contfuse)

PointFusion: Deep Sensor Fusion for 3D Bounding Box Estimation

[[Code]](https://github.com/JuliaChae/Pointfusion)

EPNet: Enhancing Point Features with Image Semantics for 3D Object Detection

[[Code]](https://github.com/happinesslz/EPNet)

Multi-Task Multi-Sensor Fusion for 3D Object Detection

3D-CVF: Generating Joint Camera and LiDAR Features Using Cross-View Spatial Feature Fusion for 3D Object Detection

[[Code]](https://github.com/rasd3/3D-CVF)

Multi-View 3D Object Detection Network for Autonomous Driving

[[Code]](https://github.com/bostondiditeam/MV3D)

Joint 3D Proposal Generation and Object Detection from View Aggregation

[[Code]](https://github.com/kujason/avod)

#### 针对自动驾驶的三阶段特征提取器的特征级融合

#### Feature-level fusion of three-stage feature extractors for autonomous driving

Multi-level and Multi-modal Feature Fusion for Accurate 3D Object Detection in Connected and Automated Vehicles

### 3.**目标级融合** | Target-level fusion

CLOCs: Camera-LiDAR Object Candidates Fusion for 3D Object Detection

[[Code]](https://github.com/pangsu0613/CLOCs)

Fast-CLOCs: Fast Camera-LiDAR Object Candidates Fusion for 3D Object Detection

LIGA-Stereo: Learning LiDAR Geometry Aware Representations for Stereo-based 3D Detector

[[Code]](https://github.com/xy-guo/LIGA-Stereo)

### 4.**不对称融合** | Asymmetric fusion

3D Object Detection Using Scale Invariant and Feature Reweighting Networks

Improving 3D Object Detection for Pedestrians with Virtual Multi-View Synthesis Orientation Estimation

MLOD: A multi-view 3D object detection based on robust feature fusion method

[[Code]](https://github.com/JianDeng2018/MLOD)

LiDAR guided Small obstacle Segmentation

[[Home]](https://small-obstacle-dataset.github.io/)

CLOCs: Camera-LiDAR Object Candidates Fusion for 3D Object Detection

[[Code]](https://github.com/pangsu0613/CLOCs/tree/spconv-removed)

ImLiDAR Cross-Sensor Dynamic Message Propagation Network for 3D Object Detection

Autonomous Vehicle Navigation with LIDAR using Path Planning

FUTR3D: A Unified Sensor Fusion Framework for 3D Detection

SuperFusion: Multilevel LiDAR-Camera Fusion for Long-Range HD Map Generation and Prediction

M-LIO: Multi-lidar, multi-IMU odometry with sensor dropout tolerance

## 三、**弱融合** | Weak fusion

### 1.**弱融合汇总** | Weak Fusion Summary

Frustum ConvNet: Sliding Frustums to Aggregate Local Point-Wise Features for Amodal 3D Object Detection

[[Code]](https://github.com/zhixinwang/frustum-convnet)

Faraway-Frustum: Dealing with Lidar Sparsity for 3D Object Detection using Fusion

[[Code]](https://github.com/dongfang-steven-yang/faraway-frustum)

Modality-Buffet for Real-Time Object Detection

SemanticVoxels: Sequential Fusion for 3D Pedestrian Detection using LiDAR Point Cloud and Semantic Segmentation

## 四、**其它融合** | Other fusion

### 1.**其它融合汇总** | Aggregate

PointAugmenting: Cross-Modal Augmentation for 3D Object Detection

### 2.**M-LIO:激光与IMU融合** | Laser and IMU Fusion

M-LIO: Multi-lidar, multi-IMU odometry with sensor dropout tolerance

### 3.**汽车底盘信息多模态融合** | Multimodal fusion of automotive chassis information

Multi-modal Fusion Technology based on Vehicle Information: A Survey 

## 五、**融合框架（代码）** | Convergence Framework(Code)

###1.**R2LIVE**

R^2^LIVE: A Robust, Real-time, LiDAR-Inertial-Visual tightly-coupled state Estimator and mapping

[[Code]](https://github.com/hku-mars/r2live)

###2.**R3LIVE**

[[R3LIVE]](https://github.com/hku-mars/r3live)

## 六、**代码大全** | Code

### 1.**Udacity Sensor Fusion Nanodegree**

[[Udacity Sensor Fusion Nanodegree Program]](https://github.com/fanweng/Udacity-Sensor-Fusion-Nanodegree)

### 2.**毫米波和相机融合的仓库**

### Millimeter wave and camera fusion in the warehouse

milliEye: A Lightweight mmWave Radar and Camera Fusion System for Robust Object Detection

[[Code]](https://github.com/sxontheway/milliEye)





