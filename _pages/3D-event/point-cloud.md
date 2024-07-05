---
title: "Research Topic: 3D & Event"
excerpt: "3D & Event"
author_profile: True
permalink: /3D-event/point-cloud.html
---

**[▶ 2024 New](/3D-event/2024-New){: style="color: rgb(191, 0, 0)"}**
**[▶ Active 3D](/3D-event/active3d){: style="color: rgb(191, 0, 0)"}**
**[▶ Passive 3D](/3D-event/passive3d){: style="color: rgb(191, 0, 0)"}**
**[▶ Event](/3D-event/event){: style="color: rgb(191, 0, 0)"}**
**[▼ Point Cloud](/3D-event/point-cloud){: style="color: rgb(191, 0, 0)"}**

## Point Cloud

**Deep-PCAC: An End-to-End Deep Lossy Compression Framework for Point Cloud Attributes** <br>
_Xihua Sheng, Li Li, Dong Liu, Zhiwei Xiong, Zhu Li, Feng Wu_ <br>
<span><pub>IEEE Transactions on Multimedia (T-MM), 2022</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/9447226){:target="\_blank"} |
[Code](https://github.com/xhsheng-ustc/Deep-PCAC){:target="\_blank"} |
<a onclick='expandABS("sheng22")'> Abstract </a>

<div style="display: none;" class=abs id="sheng22"><br>
The large data volume of point clouds poses severe challenges for efficient storage and transmission in recent years. In this paper, we propose the first -- to our best knowledge -- end-to-end deep framework for compressing point cloud attributes. Specifically, we propose a point cloud lossy attribute autoencoder, which directly encodes and decodes point cloud attributes with the help of geometry, instead of voxelizing or projecting the points. In the autoencoder, we propose a second-order point convolution that utilizes the spatial correlations between more points and the nonlinear relationship between attribute features. We introduce a dense point-inception block, which derives from a combination of an inception-style block and a dense block, to improve feature propagation. In addition, we devise a multiscale loss to guide the autoencoder in focusing attention on the coarse-grained points with better coverage of the entire point cloud, which makes it easier for the autoencoder to obtain better optimization of the qualities of all points. Experimental results show that our proposed framework still has a performance gap compared with the state-of-the-art algorithms in the MPEG G-PCC reference software TMC13. However, it does outperform the RAHT-RLGR, which is one of the core transforms used in TMC13 without many well-designed techniques that make TMC13 what it is today. It outperforms RAHT-RLGR by 2.63 dB, 1.77 dB, and 3.40 dB on average in terms of the BD-PSNR for the Y, U, and V components. A subjective quality comparison demonstrates that our framework can preserve more textures and reduce blocking and color noise artifacts.

</div>

**Attribute Artifacts Removal for Geometry-Based Point Cloud Compression** <br>
_Xihua Sheng, Li Li, Dong Liu, Zhiwei Xiong_ <br>
<span><pub>IEEE Transactions on Image Processing (T-IP), 2022</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/9767661){:target="\_blank"} |
[Code](https://github.com/xhsheng-ustc/MS-GAT){:target="\_blank"} |
<a onclick='expandABS("sheng21")'> Abstract </a>

<div style="display: none;" class=abs id="sheng21"><br>
Geometry-based point cloud compression (G-PCC) can achieve remarkable compression efficiency for point clouds. However, it still leads to serious attribute compression artifacts, especially under low bitrate scenarios. In this paper, we propose a Multi-Scale Graph Attention Network (MS-GAT) to remove the artifacts of point cloud attributes compressed by G-PCC. We first construct a graph based on point cloud geometry coordinates and then use the Chebyshev graph convolutions to extract features of point cloud attributes. Considering that one point may be correlated with points both near and far away from it, we propose a multi-scale scheme to capture the short- and long-range correlations between the current point and its neighboring and distant points. To address the problem that various points may have different degrees of artifacts caused by adaptive quantization, we introduce the quantization step per point as an extra input to the proposed network. We also incorporate a weighted graph attentional layer into the network to pay special attention to the points with more attribute artifacts. To the best of our knowledge, this is the first attribute artifacts removal method for G-PCC. We validate the effectiveness of our method over various point clouds. Objective comparison results show that our proposed method achieves an average of 9.74% BD-rate reduction compared with Predlift and 10.13% BD-rate reduction compared with RAHT. Subjective comparison results present that visual artifacts such as color shifting, blurring, and quantization noise are reduced.

</div>

**RPPformer-Flow: Relative Position Guided Point Transformer for Scene Flow Estimation** <br>
_Hanlin Li, Guanting Dong, Yueyi Zhang, Xiaoyan Sun, Zhiwei Xiong_ <br>
<span><pub>ACM International Conference on Multimedia (MM), 2022</pub></span> <br>
[Paper](https://dl.acm.org/doi/abs/10.1145/3503161.3547771){:target="\_blank"} |
[Code](https://github.com/ustc-hlli/RPPformer-Flow){:target="\_blank"} |
<a onclick='expandABS("li22")'> Abstract </a>

<div style="display: none;" class=abs id="li22"><br>
Estimating scene flow for point clouds is one of the key problems in 3D scene understanding and autonomous driving. Recently the point transformer architecture has become a popular and successful solution for 3D computer vision tasks, e.g., point cloud object detection and completion, but its application to scene flow estimation is rarely explored. In this work, we provide a full transformer based solution for scene flow estimation. We first introduce a novel relative position guided point attention mechanism. Then to relax the memory consumption in practice, we provide an efficient implementation of our proposed point attention layer via matrix factorization and nearest neighbor sampling. Finally, we build a pyramid transformer, named RPPformer-Flow, to estimate the scene flow between two consecutive point clouds in a coarse-to-fine manner. We evaluate our RPPformer-Flow on the FlyingThings3D and KITTI Scene Flow 2015 benchmarks. Experimental results show that our method outperforms previous state-of-the-art methods with large margins.
</div>

**Exploiting Rigidity Constraints for LiDAR Scene Flow Estimation** <br>
_Guanting Dong, Yueyi Zhang, Hanlin Li, Xiaoyan Sun, Zhiwei Xiong_ <br>
<span><pub>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2022</pub></span> <br>
[Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Dong_Exploiting_Rigidity_Constraints_for_LiDAR_Scene_Flow_Estimation_CVPR_2022_paper.html){:target="\_blank"} |
[Code](https://github.com/gtdong-ustc/LiDARSceneFlow){:target="\_blank"} |
<a onclick='expandABS("dong22")'> Abstract </a>

<div style="display: none;" class=abs id="dong22"><br>
Previous LiDAR scene flow estimation methods, especially recurrent neural networks, usually suffer from structure distortion in challenging cases, such as sparse reflection and motion occlusions. In this paper, we propose a novel optimization method based on a recurrent neural network to predict LiDAR scene flow in a weakly supervised manner. Specifically, our neural recurrent network exploits direct rigidity constraints to preserve the geometric structure of the warped source scene during an iterative alignment procedure. An error awarded optimization strategy is proposed to update the LiDAR scene flow by minimizing the point measurement error instead of reconstructing the cost volume multiple times. Trained on two autonomous driving datasets, our network outperforms recent state-of-the-art networks on lidarKITTI by a large margin. The code and models will be available at https://github.com/gtdong-ustc/LiDARSceneFlow.

</div>

---

**[▶ 2024 New](/3D-event/2024-New){: style="color: rgb(191, 0, 0)"}**
**[▶ Active 3D](/3D-event/active3d){: style="color: rgb(191, 0, 0)"}**
**[▶ Passive 3D](/3D-event/passive3d){: style="color: rgb(191, 0, 0)"}**
**[▶ Event](/3D-event/event){: style="color: rgb(191, 0, 0)"}**
**[▲ Point Cloud](/3D-event/point-cloud){: style="color: rgb(191, 0, 0)"}**
