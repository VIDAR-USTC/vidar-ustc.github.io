---
title: "Research Topic: 3D & Event"
excerpt: "3D & Event"
author_profile: True
permalink: /3D-event/passive3d.html
---

**[▶ 2024 New](/3D-event/2024-New){: style="color: rgb(191, 0, 0)"}**
**[▶ Acitve 3D](/3D-event/active3d){: style="color: rgb(191, 0, 0)"}**
**[▼ Passive 3D](/3D-event/passive3d){: style="color: rgb(191, 0, 0)"}**
**[▶ Event](/3D-event/event){: style="color: rgb(191, 0, 0)"}**
**[▶ Point Cloud](/3D-event/point-cloud){: style="color: rgb(191, 0, 0)"}**

## Passive 3D

**Depth Estimation From Indoor Panoramas With Neural Scene Representation** <br>
_Wenjie Chang, Yueyi Zhang, Zhiwei Xiong_ <br>
<span><pub>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2023</pub></span> <br>
[Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Chang_Depth_Estimation_From_Indoor_Panoramas_With_Neural_Scene_Representation_CVPR_2023_paper.html){:target="\_blank"} |
[Code](https://github.com/WJ-Chang-42/IndoorPanoDepth){:target="\_blank"} |
[Intro Video](https://www.youtube.com/watch?v=hxFzpgLNCDI){:target="\_blank"} |
<a onclick='expandABS("chang23")'> Abstract </a>

<div style="display: none;" class=abs id="chang23"><br>
Depth estimation from indoor panoramas is challenging due to the equirectangular distortions of panoramas and inaccurate matching. In this paper, we propose a practical framework to improve the accuracy and efficiency of depth estimation from multi-view indoor panoramic images with the Neural Radiance Field technology. Specifically, we develop two networks to implicitly learn the Signed Distance Function for depth measurements and the radiance field from panoramas. We also introduce a novel spherical position embedding scheme to achieve high accuracy. For better convergence, we propose an initialization method for the network weights based on the Manhattan World Assumption. Furthermore, we devise a geometric consistency loss, leveraging the surface normal, to further refine the depth estimation. The experimental results demonstrate that our proposed method outperforms state-of-the-art works by a large margin in both quantitative and qualitative evaluations. Our source code is available at https://github.com/WJ-Chang-42/IndoorPanoDepth.
</div>

**Degradation-Agnostic Correspondence From Resolution-Asymmetric Stereo** <br>
_Xihao Chen, Zhiwei Xiong, Zhen Cheng, Jiayong Peng, Yueyi Zhang, Zheng-Jun Zha_ <br>
<span><pub>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2022</pub></span> <br>
[Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Chen_Degradation-Agnostic_Correspondence_From_Resolution-Asymmetric_Stereo_CVPR_2022_paper.html){:target="\_blank"} |
[Code & Dataset](https://github.com/xhchen10/ResAsym_StereoMatching){:target="\_blank"} |
<a onclick='expandABS("chen22")'> Abstract </a>

<div style="display: none;" class=abs id="chen22"><br>
In this paper, we study the problem of stereo matching from a pair of images with different resolutions, e.g., those acquired with a tele-wide camera system. Due to the difficulty of obtaining ground-truth disparity labels in diverse real-world systems, we start from an unsupervised learning perspective. However, resolution asymmetry caused by unknown degradations between two views hinders the effectiveness of the generally assumed photometric consistency. To overcome this challenge, we propose to impose the consistency between two views in a feature space instead of the image space, named feature-metric consistency. Interestingly, we find that, although a stereo matching network trained with the photometric loss is not optimal, its feature extractor can produce degradation-agnostic and matching-specific features. These features can then be utilized to formulate a feature-metric loss to avoid the photometric inconsistency. Moreover, we introduce a self-boosting strategy to optimize the feature extractor progressively, which further strengthens the feature-metric consistency. Experiments on both simulated datasets with various degradations and a self-collected real-world dataset validate the superior performance of the proposed method over existing solutions.

</div>

**Transformer-Based Monocular Depth Estimation with Attention Supervision** <br>
_Wenjie Chang, Yueyi Zhang, Zhiwei Xiong_ <br>
<span><pub>British Machine Vision Conference (BMVC), 2021</pub></span> <br>
[Paper](https://www.bmvc2021-virtualconference.com/assets/papers/0244.pdf){:target="\_blank"} |
[Code](https://github.com/WJ-Chang-42/ASTransformer){:target="\_blank"} |
<a onclick='expandABS("chang21")'> Abstract </a>

<div style="display: none;" class=abs id="chang21"><br>
Transformer, which excels in capturing long-range dependencies, has shown great performance in a variety of computer vision tasks. In this paper, we propose a hybrid network with a Transformer-based encoder and a CNN-based decoder for monocular depth estimation. The encoder follows the architecture of classical Vision Transformer. To better exploit the potential of the Transformer encoder, we introduce the Attention Supervision to the Transformer layer, which enhances the representative ability. The down-sampling operations before the Transformer encoder lead to degradation of the details in the predicted depth map. Thus, we devise an Attention-based Up-sample Block and deploy it to compensate the texture features. Experiments on both indoor and outdoor datasets demonstrate that the proposed method achieves the state-of-the-art performance on both quantitative and qualitative evaluations. The source code and trained models can be downloaded at https://github.com/WJ-Chang-42/ASTransformer.

</div>

**Zero-Shot Depth Estimation from Light Field Using a Convolutional Neural Network** <br>
_Jiayong Peng, Zhiwei Xiong, Yicheng Wang, Yueyi Zhang, Dong Liu_ <br>
<span><pub>IEEE Transactions on Computational Imaging (T-CI), 2020</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/8961135/){:target="\_blank"} |
[Code](https://github.com/JiayongO-O/LFDEN){:target="\_blank"} |
<a onclick='expandABS("peng20tci")'> Abstract </a>

<div style="display: none;" class=abs id="peng20tci"><br>
This article proposes a zero-shot learning-based framework for light field depth estimation, which learns an end-to-end mapping solely from an input light field to the corresponding disparity map with neither extra training data nor supervision of groundtruth depth. The proposed method overcomes two major difficulties posed in existing learning-based methods and is thus much more feasible in practice. First, it saves the huge burden of obtaining groundtruth depth of a variety of scenes to serve as labels during training. Second, it avoids the severe domain shift effect when applied to light fields with drastically different content or captured under different camera configurations from the training data. On the other hand, compared with conventional non-learning-based methods, the proposed method better exploits the correlations in the 4D light field and generates much superior depth results. Moreover, we extend this zero-shot learning framework to depth estimation from light field videos. For the first time, we demonstrate that more accurate and robust depth can be estimated from light field videos by jointly exploiting the correlations across spatial, angular, and temporal dimensions. We conduct comprehensive experiments on both synthetic and real-world light field image datasets, as well as a self collected light field video dataset. Quantitative and qualitative results validate the superior performance of our method over the state-of-the-arts, especially for the challenging real-world scenes.

</div>

**Unsupervised Depth Estimation from Light Field Using a Convolutional Neural Network** <br>
_Jiayong Peng, Zhiwei Xiong, Dong Liu, Xuejin Chen_ <br>
<span><pub>International Conference on 3D Vision (3DV), 2018</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/8490980/){:target="\_blank"} |
[Code](https://github.com/JiayongO-O/LFDEN){:target="\_blank"} |
<a onclick='expandABS("peng18")'> Abstract </a>

<div style="display: none;" class=abs id="peng18"><br>
This paper proposes an unsupervised CNN-based method for explicit depth estimation from light field, which learns an end-to-end mapping from a 4D light field to the corresponding disparity map without the supervision of groundtruth depth. Specifically, we design a combined loss function imposing both compliance and divergence constraints on the warped sub-aperture images to the central view, which guarantees our network to generate an accurate and robust disparity map. Furthermore, we find that increasing the number of referenced views in depth feature extraction and complementing missing information caused by warping greatly boost the performance of our network. Due to the difficulty of obtaining groundtruth depth of real-world scenes in practice, the proposed method is much more feasible than supervised learning. On the other hand, compared with traditional non-learning methods, the proposed method better exploits the correlations in the 4D light field and generates superior depth results both quantitatively and qualitatively. Also, the proposed method helps improve the performance of subsequent applications based on the estimated depth, e.g., spatial super-resolution of light field.

</div>

---

**[▶ 2024 New](/3D-event/2024-New){: style="color: rgb(191, 0, 0)"}**
**[▶ Active 3D](/3D-event/active3d){: style="color: rgb(191, 0, 0)"}**
**[▲ Passive 3D](/3D-event/passive3d){: style="color: rgb(191, 0, 0)"}**
**[▶ Event](/3D-event/event){: style="color: rgb(191, 0, 0)"}**
**[▶ Point Cloud](/3D-event/point-cloud){: style="color: rgb(191, 0, 0)"}**
