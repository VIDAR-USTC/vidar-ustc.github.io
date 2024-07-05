---
title: "Research Topic: Manipulation"
excerpt: "Manipulation"
author_profile: True
permalink: /manipulation/denoising.html
---

**[▶ 2024 New](/manipulation/2024-New){: style="color: rgb(191, 0, 0)"}**
**[▶ Generation](/manipulation/editing-generation){: style="color: rgb(191, 0, 0)"}**
**[▶ Enhancement](/manipulation/hdr-enhancement){: style="color: rgb(191, 0, 0)"}**
**[▼ Denoising](/manipulation/denoising){: style="color: rgb(191, 0, 0)"}**
**[▶ Low4High](/manipulation/low-for-high){: style="color: rgb(191, 0, 0)"}**

## Denoising

**Towards Interactive Self-Supervised Denoising** <br>
_Mingde Yao, Dongliang He, Xin Li, Fu Li, Zhiwei Xiong_ <br>
<span><pub>IEEE Transactions on Circuits and Systems for Video Technology (T-CSVT), 2023</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/10059001/){:target="\_blank"} |
[Code](https://github.com/mdyao/Interact_Self_supervised_denoising){:target="\_blank"} |
<a onclick='expandABS("yao23")'> Abstract </a>

<div style="display: none;" class=abs id="yao23"><br>
Self-supervised denoising frameworks have recently been proposed to learn denoising models without noisy-clean image pairs, showing great potential in various applications. The denoising model is expected to produce visually pleasant images without noise patterns. However, it is non-trivial to achieve this goal using self-supervised methods because 1) the self-supervised model is difficult to restore the perceptual information due to the lack of clean supervision, and 2) perceptual quality is relatively subjective to users’ preferences. In this paper, we make the first attempt to build an interactive self-supervised denoising model to tackle the aforementioned problems. Specifically, we propose an interactive two-branch network to effectively restore perceptual information. The network consists of a denoising branch and an interactive branch, where the former focuses on efficient denoising, and the latter modulates the denoising branch. Based on the delicate architecture design, our network can produce various denoising outputs, allowing the user to easily select the most appealing outcome for satisfying the perceptual requirement. Moreover, to optimize the network with only noisy images, we propose a novel two-stage training strategy in a self-supervised way. Once the network is optimized, it can be interactively changed between noise reduction and texture restoration, providing more denoising choices for users. Existing self-supervised denoising methods can be integrated into our method to be user-friendly with interaction. Extensive experiments and comprehensive analyses are conducted to validate the effectiveness of the proposed method.
</div>

**Tensor-based Plenoptic Image Denoising by Integrating Super-Resolution** <br>
_Yun Liu, Na Qi, Zhiwei Xiong_ <br>
<span><pub>Signal Processing: Image Communication, 2022</pub></span> <br>
[Paper](https://www.sciencedirect.com/science/article/pii/S0923596522000996){:target="\_blank"} |
[Code](/code/SPIC_Code.zip){:target="\_blank"} |
<a onclick='expandABS("liu22")'> Abstract </a>

<div style="display: none;" class=abs id="liu22"><br>
In this paper, we propose a novel tensor-based denoising method targeting at plenoptic images which contain 4D light field (2D angular + 2D spatial) and 5D hyperspectral light field (2D angular + 2D spatial + 1D spectral). In order to make use of the high-dimension structural property of plenoptic images, we first generalize the intrinsic tensor sparsity measure to plenoptic images by extending the nonlocal similarity from the spatial dimension to the angular dimension. Second, to eliminate the sub-pixel misalignment of different views, we integrate the spatial super-resolution into denoising and exploit the spatial-angular correlation by utilizing the nonlocal similarity of the refined high-resolution central view. In the procedure of super-resolution, we utilize an intensity consistency criterion and a coordinate rationality criterion to facilitate the process of projection. The denoising performance can be boosted after back-projection performed on the refined high-resolution central view. Experimental results validate the superior performance of the proposed method on several plenoptic image datasets in terms of both subjective and objective quality.
</div>

**Real-World Image Denoising with Deep Boosting** <br>
_Chang Chen, Zhiwei Xiong, Xinmei Tian, Zheng-Jun Zha, Feng Wu_ <br>
<span><pub>IEEE Transactions on Pattern Analysis and Machine Intelligence (T-PAMI), 2020</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/8733117){:target="\_blank"} |
[Code & Dataset](https://github.com/ngchc/deepBoosting){:target="\_blank"} |
<a onclick='expandABS("chen20")'> Abstract </a>

<div style="display: none;" class=abs id="chen20"><br>
We propose a Deep Boosting Framework (DBF) for real-world image denoising by integrating the deep learning technique into the boosting algorithm. The DBF replaces conventional handcrafted boosting units by elaborate convolutional neural networks, which brings notable advantages in terms of both performance and speed. We design a lightweight Dense Dilated Fusion Network (DDFN) as an embodiment of the boosting unit, which addresses the vanishing of gradients during training due to the cascading of networks while promoting the efficiency of limited parameters. The capabilities of the proposed method are first validated on several representative simulation tasks including non-blind and blind Gaussian denoising and JPEG image deblocking. We then focus on a practical scenario to tackle with the complex and challenging real-world noise. To facilitate leaning-based methods including ours, we build a new Real-world Image Denoising (RID) dataset, which contains 200 pairs of high-resolution images with diverse scene content under various shooting conditions. Moreover, we conduct comprehensive analysis on the domain shift issue for real-world denoising and propose an effective one-shot domain transfer scheme to address this issue. Comprehensive experiments on widely used benchmarks demonstrate that the proposed method significantly surpasses existing methods on the task of real-world image denoising. Code and dataset are available at https://github.com/ngchc/deepBoosting.
</div>

**Camera Trace Erasing** <br>
_Chang Chen, Zhiwei Xiong, Xiaoming Liu, Feng Wu_ <br>
<span><pub>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2020</pub></span> <br>
[Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Chen_Camera_Trace_Erasing_CVPR_2020_paper.html){:target="\_blank"} |
[Code](https://github.com/ngchc/CameraTE){:target="\_blank"} |
<a onclick='expandABS("chen19")'> Abstract </a>

<div style="display: none;" class=abs id="chen19"><br>
Camera trace is a unique noise produced in digital imaging process. Most existing forensic methods analyze camera trace to identify image origins. In this paper, we address a new low-level vision problem, camera trace erasing, to reveal the weakness of trace-based forensic methods. A comprehensive investigation on existing anti-forensic methods reveals that it is non-trivial to effectively erase camera trace while avoiding the destruction of content signal. To reconcile these two demands, we propose Siamese Trace Erasing (SiamTE), in which a novel hybrid loss is designed on the basis of Siamese architecture for network training. Specifically, we propose embedded similarity, truncated fidelity, and cross identity to form the hybrid loss. Compared with existing anti-forensic methods, SiamTE has a clear advantage for camera trace erasing, which is demonstrated in three representative tasks.
</div>

**Deep Boosting for Image Denoising** <br>
_Chang Chen, Zhiwei Xiong, Xinmei Tian, Feng Wu_ <br>
<span><pub>European Conference on Computer Vision (ECCV), 2018</pub></span> <br>
[Paper](https://openaccess.thecvf.com/content_ECCV_2018/html/Chang_Chen_Deep_Boosting_for_ECCV_2018_paper){:target="\_blank"} |
[Code](https://github.com/ngchc/deepBoosting){:target="\_blank"} |
<a onclick='expandABS("chen18")'> Abstract </a>

<div style="display: none;" class=abs id="chen18"><br>
Boosting is a classic algorithm which has been successfully applied to diverse computer vision tasks. In the scenario of image denoising, however, the existing boosting algorithms are surpassed by the emerging learning-based models. In this paper, we propose a novel deep boosting framework (DBF) for denoising, which integrates several convolutional networks in a feed-forward fashion. Along with the integrated networks, however, the depth of the boosting framework is substantially increased, which brings difficulty to training. To solve this problem, we introduce the concept of dense connection that overcomes the vanishing of gradients during training. Furthermore, we propose a path-widening fusion scheme cooperated with the dilated convolution to derive a lightweight yet efficient convolutional network as the boosting unit, named Dilated Dense Fusion Network (DDFN). Comprehensive experiments demonstrate that our DBF outperforms existing methods on widely used benchmarks, in terms of different denoising tasks.

## </div>

**[▶ 2024 New](/manipulation/2024-New){: style="color: rgb(191, 0, 0)"}**
**[▶ Generation](/manipulation/editing-generation){: style="color: rgb(191, 0, 0)"}**
**[▶ Enhancement](/manipulation/hdr-enhancement){: style="color: rgb(191, 0, 0)"}**
**[▲ Denoising](/manipulation/denoising){: style="color: rgb(191, 0, 0)"}**
**[▶ Low4High](/manipulation/low-for-high){: style="color: rgb(191, 0, 0)"}**
