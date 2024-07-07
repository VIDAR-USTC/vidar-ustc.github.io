---
title: "Research Topic: Manipulation"
excerpt: "Manipulation"
author_profile: True
permalink: /manipulation/low-for-high.html
---

**[▶ 2024 New](/manipulation/2024-New){: style="color: rgb(191, 0, 0)"}**
**[▶ Generation](/manipulation/editing-generation){: style="color: rgb(191, 0, 0)"}**
**[▶ Enhancement](/manipulation/hdr-enhancement){: style="color: rgb(191, 0, 0)"}**
**[▶ Denoising](/manipulation/denoising){: style="color: rgb(191, 0, 0)"}**
**[▼ Low4High](/manipulation/low-for-high){: style="color: rgb(191, 0, 0)"}**

## Low-Level For High-Level

**Learning Fine-Grained Features for Pixel-Wise Video Correspondences** <br>
_Rui Li, Shenglong Zhou, Dong Liu_ <br>
<span><pub>IEEE/CVF International Conference on Computer Vision (ICCV), 2023</pub></span> <br>
[Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Li_Learning_Fine-Grained_Features_for_Pixel-Wise_Video_Correspondences_ICCV_2023_paper.html){:target="\_blank"} |
[Code](https://github.com/qianduoduolr/FGVC){:target="\_blank"} |
<a onclick='expandABS("li23iccv")'> Abstract </a>

<div style="display: none;" class=abs id="li23iccv"><br>
Video analysis tasks rely heavily on identifying the pixels from different frames that correspond to the same visual target. To tackle this problem, recent studies have advocated feature learning methods that aim to learn distinctive representations to match the pixels, especially in a self-supervised fashion. Unfortunately, these methods have difficulties for tiny or even single-pixel visual targets. Pixel-wise video correspondences were traditionally related to optical flows, which however lead to deterministic correspondences and lack robustness on real-world videos. We address the problem of learning features for establishing pixel-wise correspondences. Motivated by optical flows as well as the self-supervised feature learning, we propose to use not only labeled synthetic videos but also unlabeled real-world videos for learning fine-grained representations in a holistic framework. We adopt an adversarial learning scheme to enhance the generalization ability of the learned features. Moreover, we design a coarse-to-fine framework to pursue high computational efficiency. Our experimental results on a series of correspondence-based tasks demonstrate that the proposed method outperforms state-of-the-art rivals in both accuracy and efficiency.
</div>

**Synergy Between Semantic Segmentation and Image Denoising via Alternate Boosting** <br>
_Shunxin Xu, Ke Sun, Dong Liu, Zhiwei Xiong, Zheng-Jun Zha_ <br>
<span><pub>ACM Transactions on Multimedia Computing, Communications, and Applications (TOMM), 2023</pub></span> <br>
[Paper](https://dl.acm.org/doi/abs/10.1145/3548459){:target="\_blank"} |
[Code](https://github.com/powder21/SDABN){:target="\_blank"} |
<a onclick='expandABS("xu23tomm")'> Abstract </a>

<div style="display: none;" class=abs id="xu23tomm"><br>
The capability of image semantic segmentation may be deteriorated due to the noisy input image, where image denoising prior to segmentation may help. Both image denoising and semantic segmentation have been developed significantly with the advance of deep learning. In this work, we are interested in the synergy between these two tasks by using a holistic deep model. We observe that not only denoising helps combat the drop of segmentation accuracy due to the noisy input, but also pixel-wise semantic information boosts the capability of denoising. We then propose a boosting network to perform denoising and segmentation alternately. The proposed network is composed of multiple segmentation and denoising blocks (SDBs), each of which estimates a semantic map and then uses the map to regularize denoising. Experimental results show that the denoised image quality is improved substantially and the segmentation accuracy is improved to close to that on clean images, and segmentation and denoising are both boosted as the number of SDBs increases. On the Cityscapes dataset, using three SDBs improves the denoising quality to 34.42 dB in PSNR, and the segmentation accuracy to 66.5 in mIoU, when the additive white Gaussian noise level is 50.
</div>

**Spatial-Then-Temporal Self-Supervised Learning for Video Correspondence** <br>
_Rui Li, Dong Liu_ <br>
<span><pub>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2023</pub></span> <br>
[Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Li_Spatial-Then-Temporal_Self-Supervised_Learning_for_Video_Correspondence_CVPR_2023_paper.html){:target="\_blank"} |
[Code](https://github.com/qianduoduolr/Spa-then-Temp){:target="\_blank"} |
<a onclick='expandABS("li23")'> Abstract </a>

<div style="display: none;" class=abs id="li23"><br>
In low-level video analyses, effective representations are important to derive the correspondences between video frames. These representations have been learned in a self-supervised fashion from unlabeled images/videos, using carefully designed pretext tasks in some recent studies. However, the previous work concentrates on either spatial-discriminative features or temporal-repetitive features, with little attention to the synergy between spatial and temporal cues. To address this issue, we propose a novel spatial-then-temporal self-supervised learning method. Specifically, we firstly extract spatial features from unlabeled images via contrastive learning, and secondly enhance the features by exploiting the temporal cues in unlabeled videos via reconstructive learning. In the second step, we design a global correlation distillation loss to ensure the learning not to forget the spatial cues, and we design a local correlation distillation loss to combat the temporal discontinuity that harms the reconstruction. The proposed method outperforms the state-of-the-art self-supervised methods, as established by the experimental results on a series of correspondence-based video analysis tasks. Also, we performed ablation studies to verify the effectiveness of the two-step design as well as the distillation losses.
</div>

**Toward RAW Object Detection: A New Benchmark and a New Model** <br>
_Ruikang Xu, Chang Chen, Jingyang Peng, Cheng Li, Yibin Huang, Fenglong Song, Youliang Yan, Zhiwei Xiong_ <br>
<span><pub>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2023</pub></span> <br>
[Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Xu_Toward_RAW_Object_Detection_A_New_Benchmark_and_a_New_CVPR_2023_paper.html){:target="\_blank"} |
[Code](https://gitee.com/mindspore/models/tree/master/research/cv/RAOD){:target="\_blank"} |
[Dataset](https://openi.pcl.ac.cn/innovation_contest/innov202305091731448/datasets){:target="\_blank"} |
[Intro Video](https://www.youtube.com/watch?v=dyudIByvYKc){:target="\_blank"} |
<a onclick='expandABS("xu23cvpr")'> Abstract </a>

<div style="display: none;" class=abs id="xu23cvpr"><br>
In many computer vision applications (e.g., robotics and autonomous driving), high dynamic range (HDR) data is necessary for object detection algorithms to handle a variety of lighting conditions, such as strong glare. In this paper, we aim to achieve object detection on RAW sensor data, which naturally saves the HDR information from image sensors without extra equipment costs. We build a novel RAW sensor dataset, named ROD, for Deep Neural Networks (DNNs)-based object detection algorithms to be applied to HDR data. The ROD dataset contains a large amount of annotated instances of day and night driving scenes in 24-bit dynamic range. Based on the dataset, we first investigate the impact of dynamic range for DNNs-based detectors and demonstrate the importance of dynamic range adjustment for detection on RAW sensor data. Then, we propose a simple and effective adjustment method for object detection on HDR RAW sensor data, which is image adaptive and jointly optimized with the downstream detector in an end-to-end scheme. Extensive experiments demonstrate that the performance of detection on RAW sensor data is significantly superior to standard dynamic range (SDR) data in different situations. Moreover, we analyze the influence of texture information and pixel distribution of input data on the performance of the DNNs-based detector.
</div>

**Motion-Focused Contrastive Learning of Video Representations** <br>
_Rui Li, Yiheng Zhang, Zhaofan Qiu, Ting Yao, Dong Liu, Tao Mei_ <br>
<span><pub>IEEE/CVF International Conference on Computer Vision (ICCV), 2021</pub></span> <br>
[Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Li_Motion-Focused_Contrastive_Learning_of_Video_Representations_ICCV_2021_paper.pdf){:target="\_blank"} |
[Code](https://github.com/YihengZhang-CV/MCL-Motion-Focused-Contrastive-Learning){:target="\_blank"} |
<a onclick='expandABS("li21")'> Abstract </a>

<div style="display: none;" class=abs id="li21"><br>
Motion, as the most distinct phenomenon in a video to involve the changes over time, has been unique and critical to the development of video representation learning. In this paper, we ask the question: how important is the motion particularly for self-supervised video representation learning. To this end, we compose a duet of exploiting the motion for data augmentation and feature learning in the regime of contrastive learning. Specifically, we present a Motion-focused Contrastive Learning (MCL) method that regards such duet as the foundation. On one hand, MCL capitalizes on optical flow of each frame in a video to temporally and spatially sample the tubelets (i.e., sequences of associated frame patches across time) as data augmentations. On the other hand, MCL further aligns gradient maps of the convolutional layers to optical flow maps from spatial, temporal and spatio-temporal perspectives, in order to ground motion information in feature learning. Extensive experiments conducted on R(2+1)D backbone demonstrate the effectiveness of our MCL. On UCF101, the linear classifier trained on the representations learnt by MCL achieves 81.91% top-1 accuracy, outperforming ImageNet supervised pre-training by 6.78%. On Kinetics-400, MCL achieves 66.62% top-1 accuracy under the linear protocol.
</div>

**Recycling Discriminator: Towards Opinion-Unaware Image Quality Assessment Using Wasserstein GAN** <br>
_Yunan Zhu, Haichuan Ma, Jialun Peng, Dong Liu, Zhiwei Xiong_ <br>
<span><pub>ACM International Conference on Multimedia (MM), 2021</pub></span> <br>
[Paper](https://dl.acm.org/doi/abs/10.1145/3474085.3479234){:target="\_blank"} |
[Code](https://github.com/YunanZhu/RecycleD){:target="\_blank"} |
<a onclick='expandABS("zhu21")'> Abstract </a>

<div style="display: none;" class=abs id="zhu21"><br>
Generative adversarial networks (GANs) have been extensively used for training networks that perform image generation. After training, the discriminator in GAN was not used anymore. We propose to recycle the trained discriminator for another use: no-reference image quality assessment (NR-IQA). We are motivated by twofold facts. First, in Wasserstein GAN (WGAN), the discriminator is designed to calculate the distance between the distribution of generated images and that of real images; thus, the trained discriminator may encode the distribution of real-world images. Second, NR-IQA often needs to leverage the distribution of real-world images for assessing image quality. We then conjecture that using the trained discriminator for NR-IQA may help get rid of any human-labeled quality opinion scores and lead to a new opinion-unaware (OU) method. To validate our conjecture, we start from a restricted NR-IQA problem, that is IQA for artificially super-resolved images. We train super-resolution (SR) WGAN with two kinds of discriminators: one is to directly evaluate the entire image, and the other is to work on small patches. For the latter kind, we obtain patch-wise quality scores, and then have the flexibility to fuse the scores, e.g., by weighted average. Moreover, we directly extend the trained discriminators for authentically distorted images that have different kinds of distortions. Our experimental results demonstrate that the proposed method is comparable to the state-of-the-art OU NR-IQA methods on SR images and is even better than them on authentically distorted images. Our method provides a better interpretable approach to NR-IQA. Our code and models are available at https://github.com/YunanZhu/RecycleD.
</div>

**On The Classification-Distortion-Perception Tradeoff** <br>
_Dong Liu, Haochen Zhang, Zhiwei Xiong_ <br>
<span><pub>Advances in Neural Information Processing Systems (NeurIPS), 2019</pub></span> <br>
[Paper](https://proceedings.neurips.cc/paper/2019/hash/6c29793a140a811d0c45ce03c1c93a28-Abstract.html){:target="\_blank"} |
[Code](https://github.com/AlanZhang1995/CDP-Tradeoff){:target="\_blank"} |
<a onclick='expandABS("liu19")'> Abstract </a>

<div style="display: none;" class=abs id="liu19"><br>
Signal degradation is ubiquitous, and computational Denoising of degraded signal has been investigated for many years. Recently, it is reported that the capability of signal Denoising is fundamentally limited by the so-called perception-distortion tradeoff, i.e. the distortion and the perceptual difference between the restored signal and the ideal "original" signal cannot be made both minimal simultaneously. Distortion corresponds to signal fidelity and perceptual difference corresponds to perceptual naturalness, both of which are important metrics in practice. Besides, there is another dimension worthy of consideration--the semantic quality of the restored signal, i.e. the utility of the signal for recognition purpose. In this paper, we extend the previous perception-distortion tradeoff to the case of classification-distortion-perception (CDP) tradeoff, where we introduced the classification error rate of the restored signal in addition to distortion and perceptual difference. In particular, we consider the classification error rate achieved on the restored signal using a predefined classifier as a representative metric for semantic quality. We rigorously prove the existence of the CDP tradeoff, i.e. the distortion, perceptual difference, and classification error rate cannot be made all minimal simultaneously. We also provide both simulation and experimental results to showcase the CDP tradeoff. Our findings can be useful especially for computer vision research where some low-level vision tasks (signal restoration) serve for high-level vision tasks (visual understanding). Our code and models have been published.

 </div>

---

**[▶ 2024 New](/manipulation/2024-New){: style="color: rgb(191, 0, 0)"}**
**[▶ Generation](/manipulation/editing-generation){: style="color: rgb(191, 0, 0)"}**
**[▶ Enhancement](/manipulation/hdr-enhancement){: style="color: rgb(191, 0, 0)"}**
**[▶ Denoising](/manipulation/denoising){: style="color: rgb(191, 0, 0)"}**
**[▲ Low4High](/manipulation/low-for-high){: style="color: rgb(191, 0, 0)"}**
