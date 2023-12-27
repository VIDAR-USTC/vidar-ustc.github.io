---
title: "Research Topic: Super-Resolution"
excerpt: "Super-Resolution"
author_profile: True
permalink: /super-resolution/sr-image.html
---

__[▼ Image](/super-resolution/sr-image){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Video](/super-resolution/sr-video){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Spectrum](/super-resolution/sr-spectrum){: style="color: rgb(191, 0, 0)"}__
__[▶ Light Field](/super-resolution/sr-light-field){: style="color: rgb(191, 0, 0)"}__
<!-- [Others](/super-resolution/sr-other) -->

## Image


**On the Effectiveness of Spectral Discriminators for Perceptual Quality Improvement** <br>
*Xin Luo, Yunan Zhu, Shunxin Xu, Dong Liu* <br>
<span><pub>IEEE/CVF International Conference on Computer Vision (ICCV), 2023</pub></span> <br> 
[Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Luo_On_the_Effectiveness_of_Spectral_Discriminators_for_Perceptual_Quality_Improvement_ICCV_2023_paper.html){:target="_blank"} |
[Code](https://github.com/Luciennnnnnn/DualFormer){:target="_blank"} |
<a onclick='expandABS("luo23")'> Abstract</a> 
<div style="display: none;" class=abs id="luo23"><br>
Several recent studies advocate the use of spectral discriminators, which evaluate the Fourier spectra of images for generative modeling. However, the effectiveness of the spectral discriminators is not well interpreted yet. We tackle this issue by examining the spectral discriminators in the context of perceptual image super-resolution (i.e., GAN-based SR), as SR image quality is susceptible to spectral changes. Our analyses reveal that the spectral discriminator indeed performs better than the ordinary (a.k.a. spatial) discriminator in identifying the differences in the high-frequency range; however, the spatial discriminator holds an advantage in the low-frequency range. Thus, we suggest that the spectral and spatial discriminators shall be used simultaneously. Moreover, we improve the spectral discriminators by first calculating the patch-wise Fourier spectrum and then aggregating the spectra by Transformer. We verify the effectiveness of the proposed method twofold. On the one hand, thanks to the additional spectral discriminator, our obtained SR images have their spectra better aligned to those of the real images, which leads to a better PD tradeoff. On the other hand, our ensembled discriminator predicts the perceptual quality more accurately, as evidenced in the no-reference image quality assessment task.
</div>

**Learning Steerable Function for Efficient Image Resampling** <br>
*Jiacheng Li, Chang Chen, Wei Huang, Zhiqiang Lang, Fenglong Song, Youliang Yan, Zhiwei Xiong* <br>
<span><pub>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2023</pub></span> <br>
[Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Li_Learning_Steerable_Function_for_Efficient_Image_Resampling_CVPR_2023_paper.html){:target="_blank"} |
[Code](https://github.com/ddlee-cn/LeRF-MindSpore){:target="_blank"} | 
[Intro Video](https://www.youtube.com/watch?v=6Sgnq2AD5yw){:target="_blank"} |
[Project](https://lerf.pages.dev){:target="_blank"} |
<a onclick='expandABS("li23")'> Abstract </a>
<div style="display: none;" class=abs id="li23"><br>
Image resampling is a basic technique that is widely employed in daily applications. Existing deep neural networks (DNNs) have made impressive progress in resampling performance. Yet these methods are still not the perfect substitute for interpolation, due to the issues of efficiency and continuous resampling. In this work, we propose a novel method of Learning Resampling Function (termed LeRF), which takes advantage of both the structural priors learned by DNNs and the locally continuous assumption of interpolation methods. Specifically, LeRF assigns spatially-varying steerable resampling functions to input image pixels and learns to predict the hyper-parameters that determine the orientations of these resampling functions with a neural network. To achieve highly efficient inference, we adopt look-up tables (LUTs) to accelerate the inference of the learned neural network. Furthermore, we design a directional ensemble strategy and edge-sensitive indexing patterns to better capture local structures. Extensive experiments show that our method runs as fast as interpolation, generalizes well to arbitrary transformations, and outperforms interpolation significantly, e.g., up to 3dB PSNR gain over bicubic for x2 upsampling on Manga109.
</div>

**Zero-Shot Dual-Lens Super-Resolution** <br>
*Ruikang Xu, Mingde Yao, Zhiwei Xiong* <br>
<span><pub>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2023</pub></span> <br>
[Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Xu_Zero-Shot_Dual-Lens_Super-Resolution_CVPR_2023_paper.html){:target="_blank"} |
[Code](https://github.com/XrKang/ZeDuSR){:target="_blank"} | 
[Intro Video](https://www.youtube.com/watch?v=ChHAIGyDFAI){:target="_blank"} | 
<a onclick='expandABS("xu23")'> Abstract </a>
<div style="display: none;" class=abs id="xu23"><br>
The asymmetric dual-lens configuration is commonly available on mobile devices nowadays, which naturally stores a pair of wide-angle and telephoto images of the same scene to support realistic super-resolution (SR). Even on the same device, however, the degradation for modeling realistic SR is image-specific due to the unknown acquisition process (e.g., tiny camera motion). In this paper, we propose a zero-shot solution for dual-lens SR (ZeDuSR), where only the dual-lens pair at test time is used to learn an image-specific SR model. As such, ZeDuSR adapts itself to the current scene without using external training data, and thus gets rid of generalization difficulty. However, there are two major challenges to achieving this goal: 1) dual-lens alignment while keeping the realistic degradation, and 2) effective usage of highly limited training data. To overcome these two challenges, we propose a degradation-invariant alignment method and a degradation-aware training strategy to fully exploit the information within a single dual-lens pair. Extensive experiments validate the superiority of ZeDuSR over existing solutions on both synthesized and real-world dual-lens datasets.
</div>


**MuLUT: Cooperating Multiple Look-Up Tables for Efficient Super-Resolution** <br>
*Jiacheng Li, Chang Chen, Zhen Cheng, Zhiwei Xiong* <br>
<span><pub>European Conference on Computer Vision (ECCV), 2022</pub></span> <br>
[Paper](https://link.springer.com/chapter/10.1007/978-3-031-19797-0_14){:target="_blank"} |
[Code](https://github.com/ddlee-cn/MuLUT){:target="_blank"} | 
[Intro Video](https://youtu.be/xmvQYW7dtaE){:target="_blank"} |
[Project](https://mulut.pages.dev){:target="_blank"} |
<a onclick='expandABS("li22")'> Abstract </a>
<div style="display: none;" class=abs id="li22"><br>
The high-resolution screen of edge devices stimulates a strong demand for efficient image super-resolution (SR). An emerging research, SR-LUT, responds to this demand by marrying the look-up table (LUT) with learning-based SR methods. However, the size of a single LUT grows exponentially with the increase of its indexing capacity. Consequently, the receptive field of a single LUT is restricted, resulting in inferior performance. To address this issue, we extend SR-LUT by enabling the cooperation of Multiple LUTs, termed MuLUT. Firstly, we devise two novel complementary indexing patterns and construct multiple LUTs in parallel. Secondly, we propose a re-indexing mechanism to enable the hierarchical indexing between multiple LUTs. In these two ways, the total size of MuLUT is linear to its indexing capacity, yielding a practical method to obtain superior performance. We examine the advantage of MuLUT on five SR benchmarks. MuLUT achieves a significant improvement over SR-LUT, up to 1.1 dB PSNR, while preserving its efficiency. Moreover, we extend MuLUT to address demosaicing of Bayer-patterned images, surpassing SR-LUT on two benchmarks by a large margin.
</div>


**Camera Lens Super-Resolution** <br>
*Chang Chen, Zhiwei Xiong, Xinmei Tian, Zheng-Jun Zha, Feng Wu* <br>
<span><pub>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2019</pub></span> <br>
[Paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Chen_Camera_Lens_Super-Resolution_CVPR_2019_paper){:target="_blank"} |
[Code & Dataset](https://github.com/ngchc/CameraSR){:target="_blank"} |
<a onclick='expandABS("chen19")'> Abstract </a>
<div style="display: none;" class=abs id="chen19"><br>
Existing methods for single image super-resolution (SR) are typically evaluated with synthetic degradation models such as bicubic or Gaussian downsampling. In this paper, we investigate SR from the perspective of camera lenses, named as CameraSR, which aims to alleviate the intrinsic tradeoff between resolution (R) and field-of-view (V) in realistic imaging systems. Specifically, we view the R-V degradation as a latent model in the SR process and learn to reverse it with realistic low- and high-resolution image pairs. To obtain the paired images, we propose two novel data acquisition strategies for two representative imaging systems (i.e., DSLR and smartphone cameras), respectively. Based on the obtained City100 dataset, we quantitatively analyze the performance of commonly-used synthetic degradation models, and demonstrate the superiority of CameraSR as a practical solution to boost the performance of existing SR methods. Moreover, CameraSR can be readily generalized to different content and devices, which serves as an advanced digital zoom tool in realistic imaging systems.
</div>


---


__[▲ Image](/super-resolution/sr-image){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Video](/super-resolution/sr-video){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Spectrum](/super-resolution/sr-spectrum){: style="color: rgb(191, 0, 0)"}__
__[▶ Light Field](/super-resolution/sr-light-field){: style="color: rgb(191, 0, 0)"}__

<!-- **UDNet: Up-Down Network for Compact and Efficient Feature Representation in Image Super-Resolution** <br>
*Chang Chen, Xinmei Tian, Feng Wu, Zhiwei Xiong* <br>
<span><pub>IEEE International Conference on Computer Vision Workshops (ICCVW), 2017</pub></span> <br> 
[Paper](https://ieeexplore.ieee.org/document/8265339){:target="_blank"} |
<a onclick='expandABS("chen17")'> Abstract </a>
<div style="display: none;" class=abs id="chen17"><br>
Recently, image super-resolution (SR) using convolutional neural networks (CNNs) have achieved remarkable performance. However, there is a tradeoff between performance and speed of SR, depending on whether feature representation and learning are conducted in high-resolution (HR) or low-resolution (LR) space. Generally, to pursue real-time SR, the number of parameters in CNNs has to be restricted, which results in performance degradation. In this paper, we propose a compact and efficient feature representation for real-time SR, named up-down network (UDNet). Specifically, a novel hourglass-shape structure is introduced by combining transposed convolution and spatial aggregation. This structure enables the network to transfer the feature representations between LR and HR spaces multiple times to learn a better mapping. Comprehensive experiments demonstrate that, compared with existing CNN models, UDNet achieves real-time SR without performance degradation on widely used benchmarks.
</div>
 -->





<!-- 
**Example-Based Super-Resolution With Soft Information and Decision** <br>
*Zhiwei Xiong, Dong Xu, Xiaoyan Sun, Feng Wu* <br>
<span><pub>IEEE Transactions on Multimedia (T-MM), 2013</pub></span> <br>
[Paper](http://ieeexplore.ieee.org/document/6518133/){:target="_blank"} |
<a onclick='expandABS("xiong13")'> Abstract </a>
<div style="display: none;" class=abs id="xiong13"><br>
The one-to-one correspondence between co-occurrence image patches of two different resolutions is extensively used in example-based super-resolution (SR). Due to the dimensionality gap between low resolution (LR) and high resolution (HR) spaces, however, an LR patch may correspond to a number of HR patches in practice. This ambiguity is difficult to be overcome with examples representing a deterministic mapping. In this paper, we propose a statistical method for exploiting the one-to-many correspondence between LR and HR patches, which we call soft information and decision. Soft information means an LR patch is mapped to a pixel-wise distribution of all its possible HR counterparts, rather than a single or a limited set of HR candidates. Relying on the soft information, example-based SR is then regarded as an optimization problem to best preserve the local consistency in the recovered HR image. This problem is solved with an efficient message passing algorithm with a factor graph model. The final decision on the HR pixel value is made upon the maximum a posteriori estimation and is called a soft decision. Experimental results demonstrate the superiority of the proposed method compared with the state-of-the-art methods, in terms of both the subjective and objective quality of synthesized HR images.
</div>


**Robust Web Image/Video Super-Resolution** <br>
*Zhiwei Xiong, Xiaoyan Sun, Feng Wu* <br>
<span><pub>IEEE Transactions on Image Processing (T-IP), 2010</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/5430911/){:target="_blank"} |
<a onclick='expandABS("xiong10")'> Abstract </a>
<div style="display: none;" class=abs id="xiong10"><br>
This paper proposes a robust single-image super-resolution method for enlarging low quality web image/video degraded by downsampling and compression. To simultaneously improve the resolution and perceptual quality of such web image/video, we bring forward a practical solution which combines adaptive regularization and learning-based super-resolution. The contribution of this work is twofold. First, we propose to analyze the image energy change characteristics during the iterative regularization process, i.e., the energy change ratio between primitive (e.g., edges, ridges and corners) and nonprimitive fields. Based on the revealed convergence property of the energy change ratio, appropriate regularization strength can then be determined to well balance compression artifacts removal and primitive components preservation. Second, we verify that this adaptive regularization can steadily and greatly improve the pair matching accuracy in learning-based super-resolution. Consequently, their combination effectively eliminates the quantization noise and meanwhile faithfully compensates the missing high-frequency details, yielding robust super-resolution performance in the compression scenario. Experimental results demonstrate that our solution produces visually pleasing enlargements for various web images/videos.
</div>


**Image Hallucination with Feature Enhancement** <br>
*Zhiwei Xiong, Xiaoyan Sun, Feng Wu* <br>
<span><pub>IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2009</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/5206630/){:target="_blank"} |
<a onclick='expandABS("xiong09")'> Abstract </a>
<div style="display: none;" class=abs id="xiong09"><br>
Example-based super-resolution recovers missing high frequencies in a magnified image by learning the correspondence between co-occurrence examples at two different resolution levels. As high-resolution examples usually contain more details and are of higher dimensionality in comparison with low-resolution ones, the mapping from low-resolution to high-resolution is an ill-posed problem. Rather than imposing more complicated mapping constraints, we propose to improve the mapping accuracy by enhancing low-resolution examples in terms of mapped features, e.g., derivatives and primitives. A feature enhancement method is presented through a combination of interpolation with prefiltering and non-blind sparse prior deblurring. By enhancing low-resolution examples, unique feature information carried by high-resolution examples is decreased. This regularization reduces the intrinsic dimensionality disparity between two different resolution examples and thus improves the feature mapping accuracy. Experiments demonstrate our super-resolution scheme with feature enhancement produces high quality results both perceptually and quantitatively.

</div> -->
