---
title: "Research Topic: Biomedical Image Analysis"
excerpt: "Biomedical Image Analysis"
author_profile: True
permalink: /biomedical-imaging/registration.html
---

**[▶ 2024 New](/biomedical-imaging/2024-New){: style="color: rgb(191, 0, 0)"}**
**[▶ Segmentation](/biomedical-imaging/segmentation){: style="color: rgb(191, 0, 0)"}**
**[▼ Registration](/biomedical-imaging/registration){: style="color: rgb(191, 0, 0)"}**
**[▶ Restoration](/biomedical-imaging/restoration){: style="color: rgb(191, 0, 0)"}**
**[▶ Misc.](/biomedical-imaging/misc){: style="color: rgb(191, 0, 0)"}**

## Registration

**Self-Distilled Hierarchical Network for Unsupervised Deformable Image Registration** <br>
_Shenglong Zhou, Bo Hu, Zhiwei Xiong, Feng Wu_ <br>
<span><pub>IEEE Transactions on Medical Imaging (T-MI), 2023</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/10042453){:target="\_blank"} |
[Code](https://github.com/Blcony/SDHNet){:target="\_blank"} |
<a onclick='expandABS("zhou23")'> Abstract </a>

<div style="display: none;" class=abs id="zhou23"><br>
Unsupervised deformable image registration benefits from progressive network structures such as Pyramid and Cascade. However, existing progressive networks only consider the single-scale deformation field in each level or stage and ignore the long-term connection across non-adjacent levels or stages. In this paper, we present a novel unsupervised learning approach named Self-Distilled Hierarchical Network (SDHNet). By decomposing the registration procedure into several iterations, SDHNet generates hierarchical deformation fields (HDFs) simultaneously in each iteration and connects different iterations utilizing the learned hidden state. Specifically, hierarchical features are extracted to generate HDFs through several parallel gated recurrent units, and HDFs are then fused adaptively conditioned on themselves as well as contextual features from the input image. Furthermore, different from common unsupervised methods that only apply similarity loss and regularization loss, SDHNet introduces a novel self-deformation distillation scheme. This scheme distills the final deformation field as the teacher guidance, which adds constraints for intermediate deformation fields on deformation-value and deformation-gradient spaces respectively. Experiments on five benchmark datasets, including brain MRI and liver CT, demonstrate the superior performance of SDHNet over state-of-the-art methods with a faster inference speed and a smaller GPU memory. Code is available at https://github.com/Blcony/SDHNet.
</div>

**Recursive Decomposition Network for Deformable Image Registration** <br>
_Bo Hu, Shenglong Zhou, Zhiwei Xiong, Feng Wu_ <br>
<span><pub>IEEE Journal of Biomedical and Health Informatics (JBHI), 2022</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/9826364){:target="\_blank"} |
[Code](https://github.com/BlaiseBrain/RDN_registration){:target="\_blank"} |
<a onclick='expandABS("hu22jbhi")'> Abstract </a>

<div style="display: none;" class=abs id="hu22jbhi"><br>
Deformation decomposition serves as a good solution for deformable image registration when the deformation is large. Current deformation decomposition methods can be categorized into cascade-based methods and pyramid-based methods. However, cascade-based methods suffer from heavy computational burdens and long inference time due to their structures of repeated subnetworks, while the effectiveness of pyramid-based methods is constrained by their limited numbers of resolution levels. In this paper, to address both the insufficient and inefficient decomposition problems in current deformation decomposition methods, we propose a recursive decomposition network (RDN) to offer a novel solution for deformable image registration. Stage-wise recursion can efficiently decompose a large deformation into different pyramid estimation stages without using repeated subnetworks like in cascade-based methods. Level-wise recursion can sufficiently decompose the deformation inside each resolution level instead of only one-time estimation like in pyramid-based methods. Extensive experiments and ablation studies on two representative datasets validate the effectiveness and efficiency of our proposed RDN.
</div>

**Cross-Resolution Distillation for Efficient 3D Medical Image Registration** <br>
_Bo Hu, Shenglong Zhou, Zhiwei Xiong, Feng Wu_ <br>
<span><pub>IEEE Transactions on Circuits and Systems for Video Technology (T-CSVT), 2022</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/9782430){:target="\_blank"} | [Code](https://github.com/BlaiseBrain/CRD_registration){:target="\_blank"} |
<a onclick='expandABS("hu22csvt")'> Abstract </a>

<div style="display: none;" class=abs id="hu22csvt"><br>
Images captured in clinic such as MRI scans are usually in 3D formats with high spatial resolutions. Existing learning-based models for medical image registration consume large GPU memories and long inference time, which is difficult to be deployed in resource-limited diagnosis scenarios. To address this problem, instead of shrinking the model size as in previous works, we turn to reducing the input resolution of existing registration models and boosting their performance through knowledge distillation. Specifically, we propose a cross-resolution distillation (CRD) scheme, which is designed to train low-resolution models under the guidance of corresponding high-resolution models. Nevertheless, due to the resolution gap between features in high/low-resolution models, straightforward distillation is difficult to apply. To overcome this challenge, we first introduce a feature-shifted teacher (FST) to shift and fuse features of high/low-resolution models. Then, we exploit this teacher model to guide the learning of the low-resolution student model with distillation losses on both features and deformation fields. Finally, we only need to use the distilled student model during inference. Experimental results on four 3D medical image datasets demonstrate that the low-resolution models trained through our CRD scheme use fewer than 20% GPU memories and less than 20% inference time while achieving competitive performance compared with corresponding high-resolution models.
</div>

**Fast and Accurate Electron Microscopy Image Registration with 3D Convolution** <br>
_Shenglong Zhou, Zhiwei Xiong, Chang Chen, Xuejin Chen, Dong Liu, Yueyi Zhang, Zheng-Jun Zha, Feng Wu_ <br>
<span><pub>Int. Conf. Medical Image Computing and Computer-Assisted Intervention (MICCAI), 2019</pub></span> <br>
[Paper](https://link.springer.com/chapter/10.1007/978-3-030-32239-7_53){:target="\_blank"} |
[Code](https://github.com/Blcony/FAEMReg){:target="\_blank"} |
<a onclick='expandABS("zhou19")'> Abstract </a>

<div style="display: none;" class=abs id="zhou19"><br>
We propose an unsupervised deep learning method for serial electron microscopy (EM) image registration with fast speed and high accuracy. Current registration methods are time consuming in practice due to the iterative optimization procedure. We model the registration process as a parametric function in the form of convolutional neural networks, and optimize its parameters based on features extracted from training serial EM images in a training set. Given a new series of EM images, the deformation field of each serial image can be rapidly generated through the learned function. Specifically, we adopt a spatial transformer layer to reconstruct features in the subject image from the reference ones while constraining smoothness on the deformation field. Moreover, for the first time, we introduce the 3D convolution layer to learn the relationship between several adjacent images, which effectively reduces error accumulation in serial EM image registration. Experiments on two popular EM datasets, Cremi and FIB25, demonstrate our method can operate in an unprecedented speed while providing competitive registration accuracy compared with state-of-the-art methods, including learning-based ones.

</div>

---

**[▶ 2024 New](/biomedical-imaging/2024-New){: style="color: rgb(191, 0, 0)"}**
**[▶ Segmentation](/biomedical-imaging/segmentation){: style="color: rgb(191, 0, 0)"}**
**[▲ Registration](/biomedical-imaging/registration){: style="color: rgb(191, 0, 0)"}**
**[▶ Restoration](/biomedical-imaging/restoration){: style="color: rgb(191, 0, 0)"}**
**[▶ Misc.](/biomedical-imaging/misc){: style="color: rgb(191, 0, 0)"}**
