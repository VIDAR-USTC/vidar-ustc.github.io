---
title: "Research Topic: Manipulation"
excerpt: "Manipulation"
author_profile: True
permalink: /manipulation/editing-generation.html
---

__[▼ Generation](/manipulation/editing-generation){: style="color: rgb(191, 0, 0)"}__
__[▶ Enhancement](/manipulation/hdr-enhancement){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Restoration](/manipulation/restoration){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Low4High](/manipulation/low-for-high){: style="color: rgb(191, 0, 0)"}__


## Generation & Editing


**Reference-Guided Landmark Image Inpainting With Deep Feature Matching** <br>
*Jiacheng Li, Zhiwei Xiong, Dong Liu* <br>
<span><pub>IEEE Transactions on Circuits and Systems for Video Technology (T-CSVT), 2022</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/9840396){:target="_blank"} |
[Code](https://ddlee-cn.github.io/files/refmatch.zip){:target="_blank"} |
<a onclick='expandABS("li22csvt")'> Abstract </a>
<div style="display: none;" class=abs id="li22csvt"><br>
Despite impressive progress made by recent image inpainting methods, they often fail to predict the original content when the corrupted region contains unique structures, especially for landmark images. Applying similar images as a reference is helpful but introduces a style gap of textures, resulting in color misalignment. To this end, we propose a style-robust approach for reference-guided landmark image inpainting, taking advantage of both the representation power of learned deep features and the structural prior from the reference image. By matching deep features, our approach builds style-robust nearest-neighbor mapping vector fields between the corrupted and reference images, in which the loss of information due to corruption leads to mismatched mapping vectors. To correct these mismatched mapping vectors based on the relationship between the uncorrupted and corrupted regions, we introduce mutual nearest neighbors as reliable anchors and interpolate around these anchors progressively. Finally, based on the corrected mapping vector fields, we propose a two-step warping strategy to complete the corrupted image, utilizing the reference image as a structural “blueprint”, avoiding the style misalignment problem. Extensive experiments show that our approach effectively and robustly assists image inpainting methods in restoring unique structures in the corrupted image.

</div>




**Flow-Guided Transformer for Video Inpainting** <br>
*Kaidong Zhang, Jingjing Fu, Dong Liu* <br>
<span><pub>European Conference on Computer Vision (ECCV), 2022</pub></span> <br>
[Paper](https://link.springer.com/chapter/10.1007/978-3-031-19797-0_5){:target="_blank"} |
[Code](https://github.com/hitachinsk/FGT){:target="_blank"} |
<a onclick='expandABS("zhang22eccv")'> Abstract </a>
<div style="display: none;" class=abs id="zhang22eccv"><br>
We propose a flow-guided transformer, which innovatively leverage the motion discrepancy exposed by optical flows to instruct the attention retrieval in transformer for high fidelity video inpainting. More specially, we design a novel flow completion network to complete the corrupted flows by exploiting the relevant flow features in a local temporal window. With the completed flows, we propagate the content across video frames, and adopt the flow-guided transformer to synthesize the rest corrupted regions. We decouple transformers along temporal and spatial dimension, so that we can easily integrate the locally relevant completed flows to instruct spatial attention only. Furthermore, we design a flow-reweight module to precisely control the impact of completed flows on each spatial transformer. For the sake of efficiency, we introduce window partition strategy to both spatial and temporal transformers. Especially in spatial transformer, we design a dual perspective spatial MHSA, which integrates the global tokens to the window-based attention. Extensive experiments demonstrate the effectiveness of the proposed method qualitatively and quantitatively. Codes are available at https://github.com/hitachinsk/FGT.

</div>


**Contextual Outpainting With Object-Level Contrastive Learning** <br>
*Jiacheng Li, Chang Chen, Zhiwei Xiong* <br>
<span><pub>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2022</pub></span> <br>
[Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Li_Contextual_Outpainting_With_Object-Level_Contrastive_Learning_CVPR_2022_paper.html){:target="_blank"} |
[Code](https://mailustceducn-my.sharepoint.com/:f:/g/personal/jclee_mail_ustc_edu_cn/Elzm9EwS83JDiBuaxJOiBvIB0VuHprzuHABp6rctX37kSg?e=ottSJn){:target="_blank"} |
[Intro Video](https://youtu.be/63pItMx5UDE){:target="_blank"} |
[Demo Video](https://youtu.be/gHYbPuoEEXU){:target="_blank"} |
<a onclick='expandABS("li22cvpr")'> Abstract </a>
<div style="display: none;" class=abs id="li22cvpr"><br>
We study the problem of contextual outpainting, which aims to hallucinate the missing background contents based on the remaining foreground contents. Existing image outpainting methods focus on completing object shapes or extending existing scenery textures, neglecting the semantically meaningful relationship between the missing and remaining contents. To explore the semantic cues provided by the remaining foreground contents, we propose a novel ConTextual Outpainting GAN (CTO-GAN), leveraging the semantic layout as a bridge to synthesize coherent and diverse background contents. To model the contextual correlation between foreground and background contents, we incorporate an object-level contrastive loss to regularize the learning of cross-modal representations of foreground contents and the corresponding background semantic layout, facilitating accurate semantic reasoning. Furthermore, we improve the realism of the generated background contents via detecting generated context in adversarial training. Extensive experiments demonstrate that the proposed method achieves superior performance compared with existing solutions on the challenging COCO-stuff dataset.
</div>


**Inertia-Guided Flow Completion and Style Fusion for Video Inpainting** <br>
*Kaidong Zhang, Jingjing Fu, Dong Liu* <br>
<span><pub>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2022</pub></span> <br>
[Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Zhang_Inertia-Guided_Flow_Completion_and_Style_Fusion_for_Video_Inpainting_CVPR_2022_paper.html){:target="_blank"} |
[Code](https://github.com/hitachinsk/ISVI){:target="_blank"} |
<a onclick='expandABS("zhang22cvpr")'> Abstract </a>
<div style="display: none;" class=abs id="zhang22cvpr"><br>
Physical objects have inertia, which resists changes in the velocity and motion direction. Inspired by this, we introduce inertia prior that optical flow, which reflects object motion in a local temporal window, keeps unchanged in the adjacent preceding or subsequent frame. We propose a flow completion network to align and aggregate flow features from the consecutive flow sequences based on the inertia prior. The corrupted flows are completed under the supervision of customized losses on reconstruction, flow smoothness, and consistent ternary census transform. The completed flows with high fidelity give rise to significant improvement on the video inpainting quality. Nevertheless, the existing flow-guided cross-frame warping methods fail to consider the lightening and sharpness variation across video frames, which leads to spatial incoherence after warping from other frames. To alleviate such problem, we propose the Adaptive Style Fusion Network (ASFN), which utilizes the style information extracted from the valid regions to guide the gradient refinement in the warped regions. Moreover, we design a data simulation pipeline to reduce the training difficulty of ASFN. Extensive experiments show the superiority of our method against the state-of-the-art methods quantitatively and qualitatively. The project page is at https://github.com/hitachinsk/ISVI.
</div>


**E2I: Generative Inpainting From Edge to Image** <br>
*Shunxin Xu, Dong Liu, Zhiwei Xiong* <br>
<span><pub>IEEE Transactions on Circuits and Systems for Video Technology (T-CSVT), 2021</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/9113276){:target="_blank"} |
[Code](https://github.com/powder21/E2I-inpainting){:target="_blank"} |
<a onclick='expandABS("xu21")'> Abstract </a>
<div style="display: none;" class=abs id="xu21"><br>
Deep learning-based methods especially using convolutional neural network (CNN) and generative adversarial network (GAN) have achieved certain success for the task of image inpainting. The previous methods usually try to generate the content in the missing areas from scratch. However, these methods have difficulty in producing salient image structures that appear natural and consistent with the neighborhood, especially when the missing area is large. In this paper, we address the challenge by introducing edges into the convolutional GAN-based inpainting. We split the inpainting task into two steps: first edge generation, then edge-based image generation. We adopt CNN to accomplish the two steps and use GAN-based training, thus our method is named E2I: generative inpainting from edge to image. Specifically, we adopt a deep network-based edge detector to achieve an edgeness map of an incomplete image, then we fill-in the missing areas in the edgeness map, and finally generate the missing pixels with the assistance of the complete edgeness map. We verify the proposed method on three challenging image datasets: Places2, ImageNet, and CelebA. We also compare our method with the state-of-the-arts on the Places2 test set. Our experimental results demonstrate the superior performance of our method in producing more plausible inpainting results.

 </div>




**Generating Diverse Structure for Image Inpainting With Hierarchical VQ-VAE** <br>
*Jialun Peng, Dong Liu, Songcen Xu, Houqiang Li* <br>
<span><pub>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2021</pub></span> <br>
[Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Peng_Generating_Diverse_Structure_for_Image_Inpainting_With_Hierarchical_VQ-VAE_CVPR_2021_paper.html){:target="_blank"} |
[Code](https://github.com/USTC-JialunPeng/Diverse-Structure-Inpainting){:target="_blank"} |
<a onclick='expandABS("peng21")'> Abstract </a>
<div style="display: none;" class=abs id="peng21"><br>
Given an incomplete image without additional constraint, image inpainting natively allows for multiple solutions as long as they appear plausible. Recently, multiple-solution inpainting methods have been proposed and shown the potential of generating diverse results. However, these methods have difficulty in ensuring the quality of each solution, e.g. they produce distorted structure and/or blurry texture. We propose a two-stage model for diverse inpainting, where the first stage generates multiple coarse results each of which has a different structure, and the second stage refines each coarse result separately by augmenting texture. The proposed model is inspired by the hierarchical vector quantized variational auto-encoder (VQ-VAE), whose hierarchical architecture disentangles structural and textural information. In addition, the vector quantization in VQ-VAE enables autoregressive modeling of the discrete distribution over the structural information. Sampling from the distribution can easily generate diverse and high-quality structures, making up the first stage of our model. In the second stage, we propose a structural attention module inside the texture generation network, where the module utilizes the structural information to capture distant correlations. We further reuse the VQ-VAE to calculate two feature losses, which help improve structure coherence and texture realism, respectively. Experimental results on CelebA-HQ, Places2, and ImageNet datasets show that our method not only enhances the diversity of the inpainting solutions but also improves the visual quality of the generated multiple images. Code and models are available at: https://github.com/USTC-JialunPeng/Diverse-Structure-Inpainting.

</div>


**Semantic Image Analogy with a Conditional Single-Image GAN** <br>
*Jiacheng Li, Zhiwei Xiong, Dong Liu, Xuejin Chen, Zheng-Jun Zha* <br>
<span><pub>ACM International Conference on Multimedia (MM), 2020</pub></span> <br> 
<!-- <span><highlighted>Oral</highlighted><span> | -->
<!-- [Project](https://ddlee-cn.github.io/publication/2020-07-26-MM2020-SemIA.html){:target="_blank"} | -->
[Paper](https://dl.acm.org/doi/abs/10.1145/3394171.3413601){:target="_blank"} |
[Code](https://github.com/ddlee-cn/SemIA){:target="_blank"} |
[Intro Video](https://www.youtube.com/watch?v=3KsBr5oCJ0E){:target="_blank"} |
<a onclick='expandABS("li20")'> Abstract </a>
<div style="display: none;" class=abs id="li20"><br>
Recent image-specific Generative Adversarial Networks (GANs) provide a way to learn generative models from a single image instead of a large dataset. However, the semantic meaning of patches inside a single image is less explored. In this work, we first define the task of Semantic Image Analogy: given a source image and its segmentation map, along with another target segmentation map, synthesizing a new image that matches the appearance of the source image as well as the semantic layout of the target segmentation. To accomplish this task, we propose a novel method to model the patch-level correspondence between semantic layout and appearance of a single image by training a single-image GAN that takes semantic labels as conditional input. Once trained, a controllable redistribution of patches from the training image can be obtained by providing the expected semantic layout as spatial guidance. The proposed method contains three essential parts: 1) a self-supervised training framework, with a progressive data augmentation strategy and an alternating optimization procedure; 2) a semantic feature translation module that predicts transformation parameters in the image domain from the segmentation domain; and 3) a semantics-aware patch-wise loss that explicitly measures the similarity of two images in terms of patch distribution. Compared with existing solutions, our method generates much more realistic results given arbitrary semantic labels as conditional input.

</div>

 ---

 
__[▲ Generation](/manipulation/editing-generation){: style="color: rgb(191, 0, 0)"}__
__[▶ Enhancement](/manipulation/hdr-enhancement){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Restoration](/manipulation/restoration){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Low4High](/manipulation/low-for-high){: style="color: rgb(191, 0, 0)"}__
