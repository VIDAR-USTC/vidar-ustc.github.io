---
title: "Research Topic: Biomedical Image Analysis"
excerpt: "Biomedical Image Analysis"
author_profile: True
permalink: /biomedical-imaging/restoration.html
---

**[▶ 2024 New](/biomedical-imaging/2024-New){: style="color: rgb(191, 0, 0)"}**
**[▶ Segmentation](/biomedical-imaging/segmentation){: style="color: rgb(191, 0, 0)"}**
**[▶ Registration](/biomedical-imaging/registration){: style="color: rgb(191, 0, 0)"}**
**[▼ Restoration](/biomedical-imaging/restoration){: style="color: rgb(191, 0, 0)"}**
**[▶ Misc.](/biomedical-imaging/misc){: style="color: rgb(191, 0, 0)"}**

## Restoration

**A Unified Deep Learning Framework for ssTEM Image Restoration** <br>
_Shiyu Deng, Wei Huang, Chang Chen, Xueyang Fu, Zhiwei Xiong_ <br>
<span><pub>IEEE Transactions on Medical Imaging (T-MI), 2022</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/9844781/){:target="\_blank"} |
[Code](https://github.com/sydeng99/ssTEM-restoration){:target="\_blank"} |
<a onclick='expandABS("deng22")'> Abstract </a>

<div style="display: none;" class=abs id="deng22"><br>
Serial section transmission electron micro-scopy (ssTEM) reveals biological information at a scale of nanometer and plays an important role in the ultrastructural analysis. However, due to the imperfect preparation of biological samples, ssTEM images are usually degraded with various artifacts that greatly challenge the subsequent analysis and visualization. In this paper, we introduce a unified deep learning framework for ssTEM image restoration which addresses three main types of artifacts, i.e., Support Film Folds (SFF), Staining Precipitates (SP), and Missing Sections (MS). To achieve this goal, we first model the appearance of SFF and SP artifacts by conducting comprehensive analyses on the statistics of real degraded images, relying on which we can then simulate a large number of paired images (degraded/artifacts-free) for training a deep restoration network. Then, we design a coarse-to-fine restoration network consisting of three modules, i.e., interpolation, correction, and fusion. The interpolation module exploits the adjacent artifacts-free images for an initial restoration, while the correction module resorts to the degraded image itself to rectify the artifacts. Finally, the fusion module jointly utilizes the above two results to further improve the restoration fidelity. Experimental results on both synthetic and real test data validate the significantly improved performance of our proposed framework over existing solutions, in terms of both image restoration fidelity and neuron segmentation accuracy. To the best of our knowledge, this is the first unified deep learning framework for ssTEM image restoration from different types of artifacts. Code is available at https://github.com/sydeng99/ssTEM-restoration.

</div>

**Isotropic Reconstruction of 3D EM Images with Unsupervised Degradation Learning** <br>
_Shiyu Deng, Xueyang Fu, Zhiwei Xiong, Chang Chen, Dong Liu, Xuejin Chen, Qing Ling, Feng Wu_ <br>
<span><pub>Int. Conf. Medical Image Computing and Computer-Assisted Intervention (MICCAI), 2020</pub></span> <br>
[Paper](https://link.springer.com/chapter/10.1007/978-3-030-59722-1_16){:target="\_blank"} |
[Code](https://github.com/sydeng99/IsoRecon){:target="\_blank"} |
<a onclick='expandABS("deng20")'> Abstract </a>

<div style="display: none;" class=abs id="deng20"><br>
The isotropic reconstruction of 3D electron microscopy (EM) images with low axial resolution is of great importance for biological analysis. Existing deep learning-based methods rely on handcrafted down-scaled training data, which does not model the real degradation accurately and thus leads to unsatisfying performance in practice. To address this problem, we propose a universal and unsupervised framework to simultaneously learn the real axial degradation and the isotropic reconstruction of 3D EM images. First, we train a degradation network using unpaired low-resolution (LR) and high-resolution (HR) slices, both of which are from real data, in an adversarial manner. Then, the degradation network is further used to generate realistic LR data from HR labels to form paired training data. In this way, the generated degraded data is consistent with the real axial degradation process, which guarantees the generalization ability of subsequent reconstruction networks to the real data. Our framework has the flexibility to work with different existing reconstruction methods. Experiments on both simulated and real anisotropic EM images validate the superiority of our framework.

</div>

**Learning to Restore ssTEM Images from Deformation and Corruption** <br>
_Wei Huang, Chang Chen, Zhiwei Xiong, Yueyi Zhang, Dong Liu, Feng Wu_ <br>
<span><pub>European Conference on Computer Vision Workshops (ECCVW), 2020</pub></span> <br>
[Paper](https://link.springer.com/chapter/10.1007/978-3-030-66415-2_26){:target="\_blank"} |
<a onclick='expandABS("huang20")'> Abstract </a>

<div style="display: none;" class=abs id="huang20"><br>
Serial section transmission electron microscopy (ssTEM) plays an important role in biological research. Due to the imperfect sample preparation, however, ssTEM images suffer from inevitable artifacts that pose huge challenges for the subsequent analysis and visualization. In this paper, we propose a novel strategy for modeling the main type of degradation, i.e., Support Film Folds (SFF), by characterizing this degradation process as a combination of content deformation and corruption. Relying on that, we then synthesize a sufficient amount of paired samples (degraded/groundtruth), which enables the training of a tailored deep restoration network. To the best of our knowledge, this is the first learning-based framework for ssTEM image restoration. Experiments on both synthetic and real test data demonstrate the superior performance of our proposed method over existing solutions, in terms of both image restoration quality and neuron segmentation accuracy.

</div>

---

**[▶ 2024 New](/biomedical-imaging/2024-New){: style="color: rgb(191, 0, 0)"}**
**[▶ Segmentation](/biomedical-imaging/segmentation){: style="color: rgb(191, 0, 0)"}**
**[▶ Registration](/biomedical-imaging/registration){: style="color: rgb(191, 0, 0)"}**
**[▲ Restoration](/biomedical-imaging/restoration){: style="color: rgb(191, 0, 0)"}**
**[▶ Misc.](/biomedical-imaging/misc){: style="color: rgb(191, 0, 0)"}**
