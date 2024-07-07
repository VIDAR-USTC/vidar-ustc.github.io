---
title: "Research Topic: 3D & Event"
excerpt: "3D & Event"
author_profile: True
permalink: /3D-event/active3d.html
---

**[▶ 2024 New](/3D-event/2024-New){: style="color: rgb(191, 0, 0)"}**
**[▼ Active 3D](/3D-event/active3d){: style="color: rgb(191, 0, 0)"}**
**[▶ Passive 3D](/3D-event/passive3d){: style="color: rgb(191, 0, 0)"}**
**[▶ Event](/3D-event/event){: style="color: rgb(191, 0, 0)"}**
**[▶ Point Cloud](/3D-event/point-cloud){: style="color: rgb(191, 0, 0)"}**

## Active 3D

**Deep Non-line-of-sight Imaging from Under-scanning Measurements** <br>
_Yue Li, Yueyi Zhang, Juntian Ye, Feihu Xu, Zhiwei Xiong_ <br>
<span><pub>Advances in Neural Information Processing Systems (NeurIPS), 2023</pub></span> <br>
[Paper](https://papers.nips.cc/paper_files/paper/2023/file/b91cc0a242e6518ee731f74e82b2eebd-Paper-Conference.pdf){:target="\_blank"} |
[Code](https://github.com/Depth2World/Under-scanning_NLOS){:target="\_blank"} |
<a onclick='expandABS("li23nips")'> Abstract </a>

<div style="display: none;" class=abs id="li23nips"><br>
Active confocal non-line-of-sight (NLOS) imaging has successfully enabled seeing around corners relying on high-quality transient measurements. However, acquiring spatial-dense transient measurement is time-consuming, raising the question of how to reconstruct satisfactory results from under-scanning measurements (USM). The existing solutions, involving the traditional algorithms, however, are hindered by unsatisfactory results or long computing times. To this end, we propose the first deep-learning-based approach to NLOS imaging from USM. Our proposed end-to-end network is composed of two main components: the transient recovery network (TRN) and the volume reconstruction network (VRN). Specifically, TRN takes the under-scanning measurements as input, utilizes a multiple kernel feature extraction module and a multiple feature fusion module, and outputs sufficient-scanning measurements at the high-spatial resolution. Afterwards, VRN incorporates the linear physics prior of the light-path transport model and reconstructs the hidden volume representation. Besides, we introduce regularized constraints that enhance the perception of more local details while suppressing smoothing effects. The proposed method achieves superior performance on both synthetic data and public real-world data, as demonstrated by extensive experimental results with different under-scanning grids. Moreover, the proposed method delivers impressive robustness at an extremely low scanning grid (i.e., 8x8) and offers high-speed inference (i.e., 50 times faster than the existing iterative solution).

</div>

**Self-distilled Depth from Single-shot Structured Light with Intensity Reconstruction** <br>
_Yue Li, Jiayong Peng, Yueyi Zhang, Zhiwei Xiong_ <br>
<span><pub>IEEE Transactions on Computational Imaging (T-CI), 2023</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/document/10163879){:target="\_blank"} |
[Code](https://github.com/Depth2World/SdDI){:target="\_blank"} |
<a onclick='expandABS("li23tci")'> Abstract </a>

<div style="display: none;" class=abs id="li23tci"><br>
Depth from structured light (SL) is a mainstream approach for 3D acquisition. In this paper, we propose a unique depth reconstruction method for single-shot SL systems, which reconstructs the intensity image of the scene simultaneously. The merits of our method are twofold. First, the intensity image can be used to extract scene textures under ambient light from the captured image, parsing out the projected SL pattern and thus improving depth reconstruction performance. Second, the intensity information of the scene can be useful in many applications when additional RGB cameras are not available along with the SL system. The proposed method is realized by a dual-branch deep neural network for recovering depth and intensity, respectively, where the intermediate output of the intensity branch is fed into the depth branch. Specifically, we introduce a self-distillation strategy to facilitate training the network in an unsupervised manner.

</div>

**Boosting Photon-Efficient Image Reconstruction With A Unified Deep Neural Network** <br>
_Jiayong Peng, Zhiwei Xiong, Hao Tan, Xin Huang, Zheng-Ping Li, Feihu Xu_ <br>
<span><pub>IEEE Transactions on Pattern Analysis and Machine Intelligence (T-PAMI), 2023</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/9864284){:target="\_blank"} |
[Code](https://github.com/JiayongO-O/PENonLocal){:target="\_blank"} |
<a onclick='expandABS("peng23")'> Abstract </a>

<div style="display: none;" class=abs id="peng23"><br>
Photon-efficient imaging, which captures 3D images with single-photon sensors, has enabled a wide range of applications. However, two major challenges limit the reconstruction performance, i.e., the low photon counts accompanied by low signal-to-background ratio (SBR) and the multiple returns. In this paper, we propose a unified deep neural network that, for the first time, explicitly addresses these two challenges, and simultaneously recovers depth maps and intensity images from photon-efficient measurements. Starting from a general image formation model, our network is constituted of one encoder, where a non-local block is utilized to exploit the long-range correlations in both spatial and temporal dimensions of the raw measurement, and two decoders, which are designed to recover depth and intensity, respectively. Meanwhile, we investigate the statistics of the background noise photons and propose a noise prior block to further improve the reconstruction performance. The proposed network achieves decent reconstruction fidelity even under extremely low photon counts / SBR and heavy blur caused by the multiple-return effect, which significantly surpasses the existing methods. Moreover, our network trained on simulated data generalizes well to real-world imaging systems, which greatly extends the application scope of photon-efficient imaging in challenging scenarios with a strict limit on optical flux. Code is available at https://github.com/JiayongO-O/PENonLocal.
</div>

**NLOST: Non-Line-of-Sight Imaging With Transformer** <br>
_Yue Li, Jiayong Peng, Juntian Ye, Yueyi Zhang, Feihu Xu, Zhiwei Xiong_ <br>
<span><pub>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2023</pub></span> <br>
[Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Li_NLOST_Non-Line-of-Sight_Imaging_With_Transformer_CVPR_2023_paper.html){:target="\_blank"} |
[Code & Dataset](https://github.com/Depth2World/NLOST){:target="\_blank"} |
[Intro Video](https://www.youtube.com/watch?v=VrxrRO-KERI){:target="\_blank"} |
<a onclick='expandABS("li23cvpr")'> Abstract </a>

<div style="display: none;" class=abs id="li23cvpr"><br>
Time-resolved non-line-of-sight (NLOS) imaging is based on the multi-bounce indirect reflections from the hidden objects for 3D sensing. Reconstruction from NLOS measurements remains challenging especially for complicated scenes. To boost the performance, we present NLOST, the first transformer-based neural network for NLOS reconstruction. Specifically, after extracting the shallow features with the assistance of physics-based priors, we design two spatial-temporal self attention encoders to explore both local and global correlations within 3D NLOS data by splitting or downsampling the features into different scales, respectively. Then, we design a spatial-temporal cross attention decoder to integrate local and global features in the token space of transformer, resulting in deep features with high representation capabilities. Finally, deep and shallow features are fused to reconstruct the 3D volume of hidden scenes. Extensive experimental results demonstrate the superior performance of the proposed method over existing solutions on both synthetic data and real-world data captured by different NLOS imaging systems.
</div>

**Photon-Efficient 3D Imaging with A Non-local Neural Network** <br>
_Jiayong Peng, Zhiwei Xiong, Xin Huang, Zheng-Ping Li, Dong Liu, Feihu Xu_ <br>
<span><pub>European Conference on Computer Vision (ECCV), 2020 <highlighted>(Spotlight)</highlighted></pub></span> <br>
[Paper](https://link.springer.com/chapter/10.1007/978-3-030-58539-6_14){:target="\_blank"} |
[Code](https://github.com/JiayongO-O/PENonLocal){:target="\_blank"} |
<a onclick='expandABS("peng20")'> Abstract </a>

<div style="display: none;" class=abs id="peng20"><br>
Photon-efficient imaging has enabled a number of applications relying on single-photon sensors that can capture a 3D image with as few as one photon per pixel. In practice, however, measurements of low photon counts are often mixed with heavy background noise, which poses a great challenge for existing computational reconstruction algorithms. In this paper, we first analyze the long-range correlations in both spatial and temporal dimensions of the measurements. Then we propose a non-local neural network for depth reconstruction by exploiting the long-range correlations. The proposed network achieves decent reconstruction fidelity even under photon counts (and signal-to-background ratio, SBR) as low as 1 photon/pixel (and 0.01 SBR), which significantly surpasses the state-of-the-art. Moreover, our non-local network trained on simulated data can be well generalized to different real-world imaging systems, which could extend the application scope of photon-efficient imaging in challenging scenarios with a strict limit on optical flux. Code is available at https://github.com/JiayongO-O/PENonLocal.

</div>

**Spatial Hierarchy Aware Residual Pyramid Network for Time-of-Flight Depth Denoising** <br>
_Guanting Dong, Yueyi Zhang, Zhiwei Xiong_ <br>
<span><pub>European Conference on Computer Vision (ECCV), 2020</pub></span> <br>
[Paper](https://link.springer.com/chapter/10.1007/978-3-030-58586-0_3){:target="\_blank"} |
[Code](https://github.com/ashesknight/tof-mpi-remove){:target="\_blank"} |
<a onclick='expandABS("dong20")'> Abstract </a>

<div style="display: none;" class=abs id="dong20"><br>
Time-of-Flight (ToF) sensors have been increasingly used on mobile devices for depth sensing. However, the existence of noise, such as Multi-Path Interference (MPI) and shot noise, degrades the ToF imaging quality. Previous CNN-based methods remove ToF depth noise without considering the spatial hierarchical structure of the scene, which leads to failures in obtaining high quality depth images from a complex scene. In this paper, we propose a Spatial Hierarchy Aware Residual Pyramid Network, called SHARP-Net, to remove the depth noise by fully exploiting the geometry information of the scene in different scales. SHARP-Net first introduces a Residual Regression Module, which utilizes the depth images and amplitude images as the input, to calculate the depth residual progressively. Then, a Residual Fusion Module, summing over depth residuals from all scales, is imported to refine the depth residual by fusing multi-scale geometry information. Finally, shot noise is further eliminated by a Kernel Prediction Network. Experimental results demonstrate that our method significantly outperforms state-of-the-art ToF depth denoising methods on both synthetic and realistic datasets. The source code is available at https://github.com/ashesknight/tof-mpi-remove.

</div>

**Deep Learning Based Single-Photon 3D Imaging with Multiple Returns** <br>
_Hao Tan, Jiayong Peng, Zhiwei Xiong, Dong Liu, Xin Huang, Zheng-Ping Li, Yu Hong, Feihu Xu_ <br>
<span><pub>International Conference on 3D Vision (3DV), 2020</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/9320386/){:target="\_blank"} |
<a onclick='expandABS("tan20")'> Abstract </a>

<div style="display: none;" class=abs id="tan20"><br>
Single-photon avalanche diode (SPAD) has been widely used in active 3D imaging due to its extremely high photon sensitivity and picosecond time resolution. However, long-range active 3D imaging is still a great challenge, since only a few signal photons mixed with strong background noise can return from multiple reflectors of the scene due to the divergence of the light beam and the receiver's field of view (FoV), which would bring considerable distortion and blur to the recovered depth map. In this paper, we propose a deep learning based depth reconstruction method for long range single-photon 3D imaging where the “multiple-returns” issue exists. Specifically, we model this problem as a deblurring task and design a multi-scale convolutional neural network combined with elaborate loss functions, which promote the reconstruction of an accurate depth map with fine details and clear boundaries of objects. The proposed method achieves superior performance over several different sizes of receiver's FoV on a synthetic dataset compared with existing state-of-the-art methods and the trained model under a specific FoV has a strong generalization capability across different sizes of FoV, which is essential for practical applications. Moreover, we conduct outdoor experiments and demonstrate the effectiveness of our method in a real-world long range imaging system.

</div>

---

**[▶ 2024 New](/3D-event/2024-New){: style="color: rgb(191, 0, 0)"}**
**[▲ Active 3D](/3D-event/active3d){: style="color: rgb(191, 0, 0)"}**
**[▶ Passive 3D](/3D-event/passive3d){: style="color: rgb(191, 0, 0)"}**
**[▶ Event](/3D-event/event){: style="color: rgb(191, 0, 0)"}**
**[▶ Point Cloud](/3D-event/point-cloud){: style="color: rgb(191, 0, 0)"}**
