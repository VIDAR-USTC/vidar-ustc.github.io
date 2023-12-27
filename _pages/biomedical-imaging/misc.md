---
title: "Research Topic: Biomedical Image Analysis"
excerpt: "Biomedical Image Analysis"
author_profile: True
permalink: /biomedical-imaging/misc.html
---


__[▶ Segmentation](/biomedical-imaging/segmentation){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Registration](/biomedical-imaging/registration){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Restoration](/biomedical-imaging/restoration){: style="color: rgb(191, 0, 0)"}__
__[▼ Misc.](/biomedical-imaging/misc){: style="color: rgb(191, 0, 0)"}__


## Misc.

**DBVC: An End-to-End 3-D Deep Biomedical Video Coding Framework** <br>
*Dongmei Xue, Haichuan Ma, Li Li, Dong Liu, Zhiwei Xiong, Houqiang Li* <br>
<span><pub>IEEE Transactions on Circuits and Systems for Video Technology (T-CSVT), 2023, Early Access</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/10210614){:target="_blank"} |
<a onclick='expandABS("xue23csvt")'> Abstract </a>
<div style="display: none;" class=abs id="xue23csvt"><br>
Biomedical videos require tremendous storage space and transmission bandwidth, so efficient coding methods are urgently required. Existing methods can be roughly divided into motion-based methods and wavelet-based methods. Motion-based methods use motion estimation designed for natural videos and independently optimize prediction, transform, and entropy coding modules. Wavelet-based methods treat the more redundant time dimension exactly the same as other spatial dimensions. They are both unable to completely remove the redundant spatial-temporal information in biomedical videos. In this paper, to address these problems, we build an end-to-end framework named DBVC with 3-D motion estimation, MV coding, 3-D motion compensation, and residual coding networks for efficient 3-D biomedical video coding. First, we propose a simple yet efficient 3-D motion estimation network to extract motion information. Specifically, we obtain the region with the most intense motion by a segmentation network and then perform unsupervised motion estimation exclusively on this region. After that, to encode and decode the estimated motion vectors, we apply a 3-D autoencoder-based MV coding network. Moreover, we use a lossless learnable wavelet transform for residual coding, which makes lossless coding possible. To the best of our knowledge, this is the first end-to-end video coding framework that supports both lossy and lossless coding, thus meeting the requirements of 3-D biomedical video coding. Extensive experiments demonstrate that our framework achieves state-of-the-art performance on both 3-D biological videos and 3-D medical videos.
</div>

**aiWave: Volumetric Image Compression With 3-D Trained Affine Wavelet-Like Transform** <br>
*Dongmei Xue, Haichuan Ma, Li Li, Dong Liu, Zhiwei Xiong* <br>
<span><pub>IEEE Transactions on Medical Imaging (T-MI), 2023</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/9913439){:target="_blank"} |
<a onclick='expandABS("xue23")'> Abstract </a>
<div style="display: none;" class=abs id="xue23"><br>
Volumetric image compression has become an urgent task to effectively transmit and store images produced in biological research and clinical practice. At present, the most commonly used volumetric image compression methods are based on wavelet transform, such as JP3D. However, JP3D employs an ideal, separable, global, and fixed wavelet basis to convert input images from pixel domain to frequency domain, which seriously limits its performance. In this paper, we first design a 3-D trained wavelet-like transform to enable signal-dependent and non-separable transform. Then, an affine wavelet basis is introduced to capture the various local correlations in different regions of volumetric images. Furthermore, we embed the proposed wavelet-like transform to an end-to-end compression framework called aiWave to enable an adaptive compression scheme for various datasets. Last but not least, we introduce the weight sharing strategies of the affine wavelet-like transform according to the volumetric data characteristics in the axial direction to reduce the number of parameters. The experimental results show that: 1) when cooperating our trained 3-D affine wavelet-like transform with a simple factorized entropy coding module, aiWave performs better than JP3D and is comparable in terms of encoding and decoding complexities; 2) when adding a context module to remove signal redundancy further, aiWave can achieve a much better performance than HEVC.
</div>



**An Advanced Deep Learning Framework for Video-Based Diagnosis of ASD** <br>
*Miaomiao Cai, Mingxing Li, Zhiwei Xiong, Pengju Zhao, Enyao Li, Jiulai Tang* <br>
<span><pub>Int. Conf. Medical Image Computing and Computer-Assisted Intervention (MICCAI), 2022</pub></span> <br> 
[Paper](https://link.springer.com/chapter/10.1007/978-3-031-16440-8_42){:target="_blank"} |
[Code & Dataset](https://github.com/xiaotaiyangcmm/DASD){:target="_blank"} |
<a onclick='expandABS("cai22")'> Abstract </a>
<div style="display: none;" class=abs id="cai22"><br>
Autism spectrum disorder (ASD) is one of the most common neurodevelopmental disorders, which impairs the communication and interaction ability of patients. Intensive intervention in early ASD can effectively improve symptoms, so the diagnosis of ASD children receives significant attention. However, clinical assessment relies on experienced diagnosticians, which makes the diagnosis of ASD children difficult to popularize, especially in remote areas. In this paper, we propose a simple yet effective pipeline to diagnose ASD children, which comprises a convenient and fast strategy of video acquisition and an advanced deep learning framework. In our framework, firstly, we extract sufficient head-related features from the collected videos by a generic toolbox. Secondly, we propose a head-related characteristic (HRC) attention mechanism to select the most discriminative disease-related features adaptively. Finally, a convolutional neural network is used to diagnose ASD children by exploring the temporal information from the selected features. We also build a video dataset based on our strategy of video acquisition that contains 82 children to verify the effectiveness of the proposed pipeline. Experiments on this dataset show that our deep learning framework achieves a superior performance of ASD children diagnosis. The code and dataset will be available at https://github.com/xiaotaiyangcmm/DASD.

</div>


**Learning Neuron Stitching for Connectomics** <br>
*Xiaoyu Liu, Yueyi Zhang, Zhiwei Xiong, Chang Chen, Wei Huang, Xuejin Chen, Feng Wu* <br>
<span><pub>Int. Conf. Medical Image Computing and Computer-Assisted Intervention (MICCAI), 2021</pub></span> <br> 
[Paper](https://link.springer.com/chapter/10.1007/978-3-030-87237-3_42){:target="_blank"} |
<a onclick='expandABS("liu21")'> Abstract </a>
<div style="display: none;" class=abs id="liu21"><br>
The pipeline of connectomics usually divides the large-scale electron microscopy volumes into multiple 3D blocks and segments them independently. The segmentation results in adjacent blocks demand subtle merging so that corresponding neurons can be correctly stitched. In this paper, we propose the first deep learning based neuron stitching method for connectomics. Specifically, we densely slide a 3D window along the shared face of two adjacent blocks to generate the training and testing input. A classifier based on a 3D convolutional neural network is utilized to identify whether two instance objects from adjacent blocks should be merged. The stitching label is obtained from the in-block segmentation of dedicated blocks. Experimental results on isotropic and anisotropic datasets demonstrate that our stitching method outperforms state-of-the-art methods.
</div>



---


__[▶ Segmentation](/biomedical-imaging/segmentation){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Registration](/biomedical-imaging/registration){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Restoration](/biomedical-imaging/restoration){: style="color: rgb(191, 0, 0)"}__
__[▲ Misc.](/biomedical-imaging/misc){: style="color: rgb(191, 0, 0)"}__
