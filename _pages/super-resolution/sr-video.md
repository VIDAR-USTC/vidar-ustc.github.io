---
title: "Research Topic: Super-Resolution"
excerpt: "Super-Resolution"
author_profile: True
permalink: /super-resolution/sr-video.html
---

**[▶ 2024 New](/super-resolution/2024-New){: style="color: rgb(191, 0, 0)"}**
**[▶ Image](/super-resolution/sr-image){: style="color: rgb(191, 0, 0)"}**
**[▼ Video](/super-resolution/sr-video){: style="color: rgb(191, 0, 0)"}**
**[▶ Spectrum](/super-resolution/sr-spectrum){: style="color: rgb(191, 0, 0)"}**
**[▶ Light Field](/super-resolution/sr-light-field){: style="color: rgb(191, 0, 0)"}**

## Video

**Propagating Difference Flows for Efficient Video Super-Resolution** <br>
_Ruisheng Gao, Zeyu Xiao, Zhiwei Xiong_ <br>
<span><pub>British Machine Vision Conference (BMVC), 2022</pub></span> <br>
[Paper](https://bmvc2022.mpi-inf.mpg.de/0060.pdf){:target="\_blank"} |
[Code](https://github.com/RSGao/DFlow_BasicSR){:target="\_blank"} |
<a onclick='expandABS("gao22")'> Abstract </a>

<div style="display: none;" class=abs id="gao22"><br>RSGao/FDFlow_BasicSR
Recent years have witnessed the advancement of video super-resolution (VSR) with elaborately-designed multi-frame alignment and space-time fusion/refinement techniques. However, both techniques require heavy computational burden and memory consumption, hindering existing VSR networks from being deployed on resource-constrained platforms (e.g., smartphones and wearable devices). In this paper, we propose an efficient and lightweight VSR network with two special designs. First, we propose a novelmotion propagation scheme which propagates difference flowsfor efficient feature alignment. The difference flow is sparse and computational-friendly which focuses on texture details. After estimating the preliminary difference flow with an initial motion estimator, we then design an adaptive motion modification module for frame-pair wise adaptation through bidirectional propagation. Second, a dense feature distillation module is designed for further refining the aligned features efficiently. Thanks to both designs, ournetwork achieves comparable performance with state-of-the-art VSR methods while enjoying a clear advantage in model size and computational efficiency
</div>

**Stereo Video Super-Resolution via Exploiting View-Temporal Correlation** <br>
_Ruikang Xu, Zeyu Xiao, Mingde Yao, Yueyi Zhang, Zhiwei Xiong_ <br>
<span><pub>ACM International Conference on Multimedia (MM), 2021</pub></span> <br>
[Paper](https://dl.acm.org/doi/10.1145/3474085.3475189){:target="\_blank"} |
<a onclick='expandABS("xu21")'> Abstract </a>

<div style="display: none;" class=abs id="xu21"><br>
Stereo Video Super-Resolution (StereoVSR) aims to generate high-resolution video steams from two low-resolution videos under stereo settings. Existing video super-resolution and stereo image super-resolution techniques can be extended to tackle the StereoVSR task, yet they cannot make full use of the multi-view and temporal information to achieve satisfactory performance. In this paper, we propose a novel Stereo Video Super-Resolution Network (SVSRNet) to fulfill the StereoVSR task via exploiting view-temporal correlations. First, we devise a view-temporal attention module (VTAM) to integrate the information of cross-time-cross-view for constructing high-resolution stereo videos. Second, we propose a spatial-temporal fusion module (STFM), which aggregates the information across time in intra-view to emphasize important features for subsequent restoration. In addition, we design a view-temporal consistency loss function to enforce consistency constraint of superresolved stereo videos. Comprehensive experimental results demonstrate that our method generates superior results.
</div>

**Space-Time Distillation for Video Super-Resolution** <br>
_Zeyu Xiao, Xueyang Fu, Jie Huang, Zhen Cheng, Zhiwei Xiong_ <br>
<span><pub>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2021</pub></span> <br>
[Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Xiao_Space-Time_Distillation_for_Video_Super-Resolution_CVPR_2021_paper){:target="\_blank"} |
<a onclick='expandABS("xiao21")'> Abstract </a>

<div style="display: none;" class=abs id="xiao21"><br>
Compact video super-resolution (VSR) networks can be easily deployed on resource-limited devices, e.g., smart-phones and wearable devices, but have considerable performance gaps compared with complicated VSR networks that require a large amount of computing resources. In this paper, we aim to improve the performance of compact VSR networks without changing their original architectures, through a knowledge distillation approach that transfers knowledge from a complicated VSR network to a compact one. Specifically, we propose a space-time distillation (STD) scheme to exploit both spatial and temporal knowledge in the VSR task. For space distillation, we extract spatial attention maps that hints the high-frequency video content from both networks, which are further used for transferring spatial modeling ability. For time distillation, we narrow the performance gap between compact models and complicated models by distilling the feature similarity of the temporal memory cells, which is encoded from the sequence of feature maps generated in the training clips using ConvLSTM. During the training process, STD can be easily incorporated into any network without changing the original network architecture. Experimental results on standard benchmarks demonstrate that, in resource-constrained situations, the proposed method notably improve the performance of existing VSR networks without increasing the inference time.
</div>

**Space-Time Video Super-Resolution Using Temporal Profiles** <br>
_Zeyu Xiao, Zhiwei Xiong, Xueyang Fu, Dong Liu, Zheng-Jun Zha_ <br>
<span><pub>ACM International Conference on Multimedia (MM), 2020</pub></span> <br>

<!-- <span><highlighted>Oral</highlighted><span> | -->

[Paper](https://dl.acm.org/doi/10.1145/3394171.3413667){:target="\_blank"} |
<a onclick='expandABS("xiao20")'> Abstract </a>

<div style="display: none;" class=abs id="xiao20"><br>
In this paper, we propose a novel space-time video super-resolution method, which aims to recover a high-frame-rate and high-resolution video from its low-frame-rate and low-resolution observation. Existing solutions seldom consider the spatial-temporal correlation and the long-term temporal context simultaneously and thus are limited in the restoration performance. Inspired by the epipolar-plane image used in multi-view computer vision tasks, we first propose the concept of temporal-profile super-resolution to directly exploit the spatial-temporal correlation in the long-term temporal context. Then, we specifically design a feature shuffling module for spatial retargeting and spatial-temporal information fusion, which is followed by a refining module for artifacts alleviation and detail enhancement. Different from existing solutions, our method does not require any explicit or implicit motion estimation, making it lightweight and flexible to handle any number of input frames. Comprehensive experimental results demonstrate that our method not only generates superior space-time video super-resolution results but also retains competitive implementation efficiency.
</div>

**Two-Stream Action Recognition-Oriented Video Super-Resolution** <br>
_Haochen Zhang, Dong Liu, Zhiwei Xiong_ <br>
<span><pub>IEEE/CVF International Conference on Computer Vision (ICCV), 2019</pub></span> <br>
[Paper](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Two-Stream_Action_Recognition-Oriented_Video_Super-Resolution_ICCV_2019_paper.pdf){:target="\_blank"} |
[Code](https://github.com/AlanZhang1995/TwoStreamSR){:target="\_blank"} |
<a onclick='expandABS("zhang19")'> Abstract </a>

<div style="display: none;" class=abs id="zhang19"><br>
We study the video super-resolution (SR) problem for facilitating video analytics tasks, e.g. action recognition, instead of for visual quality. The popular action recognition methods based on convolutional networks, exemplified by two-stream networks, are not directly applicable on video of low spatial resolution. This can be remedied by performing video SR prior to recognition, which motivates us to improve the SR procedure for recognition accuracy. Tailored for two-stream action recognition networks, we propose two video SR methods for the spatial and temporal streams respectively. On the one hand, we observe that regions with action are more important to recognition, and we propose an optical-flow guided weighted mean-squared-error loss for our spatial-oriented SR (SoSR) network to emphasize the reconstruction of moving objects. On the other hand, we observe that existing video SR methods incur temporal discontinuity between frames, which also worsens the recognition accuracy, and we propose a siamese network for our temporal-oriented SR (ToSR) training that emphasizes the temporal continuity between consecutive frames. We perform experiments using two state-of-the-art action recognition networks and two well-known datasets--UCF101 and HMDB51. Results demonstrate the effectiveness of our proposed SoSR and ToSR in improving recognition accuracy.
</div>

**Convolutional Neural Network-Based Video Super-Resolution for Action Recognition** <br>
_Haochen Zhang, Dong Liu, Zhiwei Xiong_ <br>
<span><pub>IEEE International Conference on Automatic Face & Gesture Recognition (FG), 2018</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/8373910/){:target="\_blank"} |
<a onclick='expandABS("zhang18")'> Abstract </a>

<div style="display: none;" class=abs id="zhang18"><br>
For video action recognition, convolutional neural networks (CNNs) especially two-stream CNNs have achieved remarkable progress in the recent years. However, most of the CNNs for action recognition are trained with high-resolution videos and not scale invariant, making it problematic to apply the trained CNNs directly on low-resolution videos. One possible solution to the problem is performing super-resolution (SR) prior to action recognition. In this paper, we investigate the effects of CNN-based video SR on the action recognition accuracy. We adopt a well trained two-stream CNN for action recognition, and analyze the spatial and temporal streams separately. For the spatial stream, we observe that video SR may improve the PSNR but may incur drop in recognition accuracy, this phenomenon is further analyzed in this paper. For the temporal stream, we observe that frame-by-frame SR may produce temporal inconsistency between consecutive video frames, which also incurs drop in recognition accuracy. We then propose a temporal consistency-oriented method for video SR, which indeed improves the recognition accuracy. Finally, we perform proper fusion of the two streams, and achieve a recognition accuracy of 88.95% on the UCF101 dataset when the input video is down-sampled by a factor of 4, compared to 93.49% accuracy on the original-resolution videos.
</div>

---

**[▶ 2024 New](/super-resolution/2024-New){: style="color: rgb(191, 0, 0)"}**
**[▶ Image](/super-resolution/sr-image){: style="color: rgb(191, 0, 0)"}**
**[▲ Video](/super-resolution/sr-video){: style="color: rgb(191, 0, 0)"}**
**[▶ Spectrum](/super-resolution/sr-spectrum){: style="color: rgb(191, 0, 0)"}**
**[▶ Light Field](/super-resolution/sr-light-field){: style="color: rgb(191, 0, 0)"}**
