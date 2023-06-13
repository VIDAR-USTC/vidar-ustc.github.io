---
title: "Research Topic: Manipulation"
excerpt: "Manipulation"
author_profile: True
permalink: /manipulation/hdr-enhancement.html
---


__[▶ Generation](/manipulation/editing-generation){: style="color: rgb(191, 0, 0)"}__
__[▼ Enhancement](/manipulation/hdr-enhancement){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Restoration](/manipulation/restoration){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Low4High](/manipulation/low-for-high){: style="color: rgb(191, 0, 0)"}__



## Enhancement & HDR

**Region-Aware Portrait Retouching with Sparse Interactive Guidance** <br>
*Huimin Zeng, Jie Huang, Jiacheng Li, Zhiwei Xiong* <br>
<span><pub>IEEE Transactions on Multimedia (T-MM), 2023, Early Access</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/10081407){:target="_blank"} |
[Code](https://github.com/ZeldaM1/interactive_portrat_retouching){:target="_blank"} |
<a onclick='expandABS("zeng23")'> Abstract </a>
<div style="display: none;" class=abs id="zeng23"><br>
Portrait retouching aims to improve the aesthetic quality of input portrait photos and especially requires human-region priority. The deep learning-based methods largely elevate the retouching efficiency and provide promising retouched results. However, existing portrait retouching methods focus on automatic retouching, which treats all human-regions equally and ignores users' preferences for specific individuals, thus suffering from limited flexibility in interactive scenarios. In this work, we emphasize the importance of users' intents and explore the interactive portrait retouching task. Specifically, we propose a region-aware retouching framework with two branches: an automatic branch and an interactive branch. The automatic branch involves an encoding-decoding process, which searches region candidates and performs automatic region-aware retouching without user guidance. The interactive branch encodes sparse user guidance into a priority condition vector and modulates latent features with a region selection module to further emphasize the user-specified regions. Experimental results show that our interactive branch effectively captures users' intents and generalizes well to unseen scenes with sparse user guidance, while our automatic branch also outperforms the state-of-the-art retouching methods due to improved region-awareness.
</div>


**Bidirectional Translation Between UHD-HDR and HD-SDR Videos** <br>
*Mingde Yao, Dongliang He, Xin Li, Zhihong Pan, Zhiwei Xiong* <br>
<span><pub>IEEE Transactions on Multimedia (T-MM), 2023, Early Access</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/10025794/){:target="_blank"} |
[Code](https://github.com/mdyao/HDR-BiTNet){:target="_blank"} |
<a onclick='expandABS("yao22")'> Abstract </a>
<div style="display: none;" class=abs id="yao22"><br>
With the popularization of ultra high definition (UHD) high dynamic range (HDR) displays, recent works focus on upgrading high definition (HD) standard dynamic range (SDR) videos to UHD-HDR versions, aiming to provides richer details and higher contrasts on advanced modern displays. However, joint considering the upgrading & downgrading translations between two types of videos, which is practical in real applications, is generally neglected. On the one hand, downgrading translation is the key to showing UHD-HDR videos on HD-SDR displays. On the other hand, considering both translations enables joint optimization and results in high quality translation. To this end, we propose the bidirectional translation network (BiT-Net), which jointly considers two translations in one network for the first time. In brief, BiT-Net is elaborately designed in an invertible fashion that can be efficiently inferred along forward and backward directions for downgrading and upgrading tasks, respectively. Based on this framework, we divide each direction into three sub-tasks, i.e. , decomposition, structure-guided translation, and synthesis, to effectively translate the dynamic range and the high-frequency details. Benefiting from the dedicated architecture, our BiT-Net can work on 1) downgrading UHD-HDR videos, 2) upgrading existing HD-SDR videos, and 3) synthesizing UHD-HDR versions from the downgraded HD-SDR videos. Experiments show that the proposed method achieves state-of-the-art performances on all these three tasks.
</div>



**Low-Light Stereo Image Enhancement** <br>
*Jie Huang, Xueyang Fu, Zeyu Xiao, Feng Zhao, Zhiwei Xiong* <br>
<span><pub>IEEE Transactions on Multimedia (T-MM), 2022, Early Access</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/9720943){:target="_blank"} |
[Code](https://github.com/KevinJ-Huang/Stereo-Low-Light){:target="_blank"} |
<a onclick='expandABS("huang22")'> Abstract </a>
<div style="display: none;" class=abs id="huang22"><br>
Stereo cameras are now commonly used in more and more devices. Nevertheless, visually unpleasant images captured under low-light conditions hinder their practical application. As an initial attempt at low-light stereo image enhancement, we propose a novel Dual-View Enhancement Network (DVENet) based on the Retinex theory, which consists of two stages. The first stage estimates an illumination map to obtain a coarse enhancement result, which boosts the correlation of two views, while the second stage recovers details by integrating the information from two views to achieve fine image quality improvement with the guidance of the illumination map. To fully utilize the dual-view correlation, we further design a wavelet-based view transfer module to efficiently carry out multi-scale detail recovery. Then, we design an illumination-aware attention fusion module to exploit the complementarity between the fused features from two views and the single-view features. Experiments on both synthetic and real-world stereo datasets demonstrate the superiority of our proposed method over existing solutions.
</div>


**Towards Real-World HDRTV Reconstruction: A Data Synthesis-Based Approach** <br>
*Zhen Cheng, Tao Wang, Yong Li, Fenglong Song, Chang Chen, Zhiwei Xiong* <br>
<span><pub>European Conference on Computer Vision (ECCV), 2022</pub></span> <br>
[Paper](https://link.springer.com/chapter/10.1007/978-3-031-19800-7_12){:target="_blank"} |
[Dataset](https://github.com/huawei-noah/benchmark/tree/main/RealHDRTV_dataset){:target="_blank"} |
<a onclick='expandABS("cheng22")'> Abstract </a>
<div style="display: none;" class=abs id="cheng22"><br>
Existing deep learning based HDRTV reconstruction methods assume one kind of tone mapping operators (TMOs) as the degradation procedure to synthesize SDRTV-HDRTV pairs for supervised training. In this paper, we argue that, although traditional TMOs exploit efficient dynamic range compression priors, they have several drawbacks on modeling the realistic degradation: information over-preservation, color bias and possible artifacts, making the trained reconstruction networks hard to generalize well to real-world cases. To solve this problem, we propose a learning-based data synthesis approach to learn the properties of real-world SDRTVs by integrating several tone mapping priors into both network structures and loss functions. In specific, we design a conditioned two-stream network with prior tone mapping results as a guidance to synthesize SDRTVs by both global and local transformations. To train the data synthesis network, we form a novel self-supervised content loss to constraint different aspects of the synthesized SDRTVs at regions with different brightness distributions and an adversarial loss to emphasize the details to be more realistic. To validate the effectiveness of our approach, we synthesize SDRTV-HDRTV pairs with our method and use them to train several HDRTV reconstruction networks. Then we collect two inference datasets containing both labeled and unlabeled real-world SDRTVs, respectively. Experimental results demonstrate that, the networks trained with our synthesized data generalize significantly better to these two real-world datasets than existing solutions.
</div>







**Hybrid Image Enhancement With Progressive Laplacian Enhancing Unit** <br>
*Jie Huang, Zhiwei Xiong, Xueyang Fu, Dong Liu, Zheng-Jun Zha* <br>
<span><pub>ACM International Conference on Multimedia (MM), 2019</pub></span> <br> 
[Paper](https://dl.acm.org/doi/abs/10.1145/3343031.3350855){:target="_blank"} |
<a onclick='expandABS("huang19")'> Abstract </a>
<div style="display: none;" class=abs id="huang19"><br>
In this paper, we propose a novel hybrid network with Laplacian enhancing unit for image enhancement. We combine the merits of two representative enhancement methods, i.e., the scaling scheme and the generative scheme, by forming a hybrid enhancing module. Meanwhile, we model image enhancement in a progressive manner with a deep cascading CNN architecture, in which the previous feature maps are used to enhance subsequent features to get an improved performance. Specifically, we propose a Laplacian enhancing unit, which can adjustably enhance the detail information by adding the residual of previous feature maps. This unit is embedded across layers for progressively enhancing the features. We build our network on the U-Net architecture and name it Hybrid Progressive Enhancing U-Net. Experiments show that our method achieves superior image enhancement results compared with the state-of-the-arts, while retaining competitive implementation efficiency.
</div>


 ---

 
__[▶ Generation](/manipulation/editing-generation){: style="color: rgb(191, 0, 0)"}__
__[▲ Enhancement](/manipulation/hdr-enhancement){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Restoration](/manipulation/restoration){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Low4High](/manipulation/low-for-high){: style="color: rgb(191, 0, 0)"}__
