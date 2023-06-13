---
title: "Research Topic: Super-Resolution"
excerpt: "Super-Resolution"
author_profile: True
permalink: /super-resolution/sr-spectrum.html
---


__[▶ Image](/super-resolution/sr-image){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Video](/super-resolution/sr-video){: style="color: rgb(191, 0, 0)"}__ 
__[▼ Spectrum](/super-resolution/sr-spectrum){: style="color: rgb(191, 0, 0)"}__
__[▶ Light Field](/super-resolution/sr-light-field){: style="color: rgb(191, 0, 0)"}__



## Spectrum

**Continuous Spectral Reconstruction from RGB Images via Implicit Neural Representation** <br>
*Ruikang Xu, Mingde Yao, Chang Chen, Lizhi Wang, Zhiwei Xiong* <br>
<span><pub>European Conference on Computer Vision Workshops (ECCVW), 2022</pub></span> <br>
<span><highlighted>Best Paper Honorable Mention Award</highlighted> of Mobile Intelligent Photography & Imaging Workshop<span> <br>
[Paper](https://link.springer.com/chapter/10.1007/978-3-031-25072-9_6){:target="_blank"} |
<a onclick='expandABS("xu22")'> Abstract </a>
<div style="display: none;" class=abs id="xu22"><br>
Existing methods for spectral reconstruction usually learn a discrete mapping from RGB images to a number of spectral bands. However, this modeling strategy ignores the continuous nature of spectral signature. In this paper, we propose Neural Spectral Reconstruction (NeSR) to lift this limitation, by introducing a novel continuous spectral representation. To this end, we embrace the concept of implicit function and implement a parameterized embodiment with a neural network. Specifically, we first adopt a backbone network to extract spatial features of RGB inputs. Based on it, we devise Spectral Profile Interpolation (SPI) module and Neural Attention Mapping (NAM) module to enrich deep features, where the spatial-spectral correlation is involved for a better representation. Then, we view the number of sampled spectral bands as the coordinate of continuous implicit function, so as to learn the projection from deep features to spectral intensities. Extensive experiments demonstrate the distinct advantage of NeSR in reconstruction accuracy over baseline methods. Moreover, NeSR extends the flexibility of spectral reconstruction by enabling an arbitrary number of spectral bands as the target output.
</div>

**Spectral-Depth Imaging with Deep Learning Based Reconstruction** <br>
*Mingde Yao, Zhiwei Xiong, Lizhi Wang, Dong Liu, Xuejin Chen* <br>
<span><pub>Optics Express (OE), 2019</pub></span> <br>
[Paper](https://opg.optica.org/oe/fulltext.cfm?uri=oe-27-26-38312&id=424648){:target="_blank"} |
<a onclick='expandABS("yao19")'> Abstract </a>
<div style="display: none;" class=abs id="yao19"><br>
We develop a compact imaging system to enable simultaneous acquisition of the spectral and depth information in real time. Our system consists of a spectral camera with low spatial resolution and an RGB camera with high spatial resolution, which captures two measurements from two different views of the same scene at the same time. Relying on an elaborate computational reconstruction algorithm with deep learning, our system can eventually obtain a spectral cube with a spatial resolution of 1920 × 1080 and a total of 16 spectral bands in the visible light section, as well as the corresponding depth map with the same spatial resolution. Quantitative and qualitative results on benchmark datasets and real-world scenes show that our reconstruction results are accurate and reliable. To the best of our knowledge, this is the first attempt to capture 5D information (3D space + 1D spectrum + 1D time) with a miniaturized apparatus and without active illumination.
</div>




**Deep Residual Attention Network for Spectral Image Super-Resolution** <br>
*Zhan Shi, Chang Chen, Zhiwei Xiong, Dong Liu, Zheng-Jun Zha, Feng Wu* <br>
<span><pub>European Conference on Computer Vision Workshops (ECCVW), 2018</pub></span> <br>
<span><highlighted>Winner</highlighted> of PIRM 2018 Challenge on Spectral Image Super-Resolution<span> <br>
[Paper](https://link.springer.com/chapter/10.1007/978-3-030-11021-5_14){:target="_blank"} |
[Code](https://github.com/contstriver/DRAN){:target="_blank"} |
<a onclick='expandABS("shi18eccv")'> Abstract </a>
<div style="display: none;" class=abs id="shi18eccv"><br>
Spectral imaging sensors often suffer from low spatial resolution, as there exists an essential tradeoff between the spectral and spatial resolutions that can be simultaneously achieved, especially when the temporal resolution needs to be retained. In this paper, we propose a novel deep residual attention network for the spatial super-resolution (SR) of spectral images. The proposed method extends the classic residual network by 1) directly using the 3D low-resolution (LR) spectral image as input instead of upsampling the 2D bandwise images separately, and 2) integrating the channel attention mechanism into the residual network. These two operations fully exploit the correlations across both the spectral and spatial dimensions and greatly promote the performance of spectral image SR. In addition, for the scenario when stereo pairs of LR spectral and high-resolution (HR) RGB measurements are available, we design a fusion framework based on the proposed network. The spatial resolution of the spectral input is enhanced in one branch, while the spectral resolution of the RGB input is enhanced in the other. These two branches are then fused together through the attention mechanism again to reconstruct the final HR spectral image, which achieves further improvement compared to using the single LR spectral input. Experimental results demonstrate the superiority of the proposed method over plain residual networks, and our method is one of the winning solutions in the PIRM 2018 Spectral Super-resolution Challenge.
</div>


**HSCNN+: Advanced CNN-Based Hyperspectral Recovery From RGB Images** <br>
*Zhan Shi, Chang Chen, Zhiwei Xiong, Dong Liu, Feng Wu* <br>
<span><pub>IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW), 2018</pub></span> <br> 
<span><highlighted>Winner</highlighted> of NTIRE 2018 Challenge on Spectral Reconstruction from RGB Images<span> <br>
[Paper](http://openaccess.thecvf.com/content_cvpr_2018_workshops/w13/html/Shi_HSCNN_Advanced_CNN-Based_CVPR_2018_paper){:target="_blank"} |
[Code](https://github.com/ngchc/HSCNN-Plus){:target="_blank"} |
<a onclick='expandABS("shi18cvpr")'> Abstract </a>
<div style="display: none;" class=abs id="shi18cvpr"><br>
Hyperspectral recovery from a single RGB image has seen a great improvement with the development of deep convolutional neural networks (CNNs). In this paper, we propose two advanced CNNs for the hyperspectral reconstruction task, collectively called HSCNN+. We first develop a deep residual network named HSCNN-R, which comprises a number of residual blocks. The superior performance of this model comes from the modern architecture and optimization by removing the hand-crafted upsampling in HSCNN. Based on the promising results of HSCNN-R, we propose another distinct architecture that replaces the residual block by the dense block with a novel fusion scheme, leading to a new network named HSCNN-D. This model substantially deepens the network structure for a more accurate solution. Experimental results demonstrate that our proposed models significantly advance the state-of-the-art. In the NTIRE 2018 Spectral Reconstruction Challenge, our entries rank the 1st (HSCNN-D) and 2nd (HSCNN-R) places on both the "Clean" and "Real World" tracks.
</div>


**HSCNN: CNN-Based Hyperspectral Image Recovery from Spectrally Undersampled Projections** <br>
*Zhiwei Xiong, Zhan Shi, Huiqun Li, Lizhi Wang, Dong Liu, Feng Wu* <br>
<span><pub>IEEE International Conference on Computer Vision Workshops (ICCVW), 2017</pub></span> <br>
[Paper](http://openaccess.thecvf.com/content_ICCV_2017_workshops/w9/html/Xiong_HSCNN_CNN-Based_Hyperspectral_ICCV_2017_paper){:target="_blank"} |
<a onclick='expandABS("xiong17iccvw")'> Abstract </a>
<div style="display: none;" class=abs id="xiong17iccvw"><br>
This paper presents a unified deep learning framework to recover hyperspectral images from spectrally undersampled projections. Specifically, we investigate two kinds of representative projections, RGB and compressive sensing (CS) measurements. These measurements are first upsampled in the spectral dimension through simple interpolation or CS reconstruction, and the proposed method learns an end-to-end mapping from a large number of upsampled/groundtruth hyperspectral image pairs. The mapping is represented as a deep convolutional neural network (CNN) that takes the spectrally upsampled image as input and outputs the enhanced hyperspetral one. We explore different network configurations to achieve high reconstruction fidelity. Experimental results on a variety of test images demonstrate significantly improved performance of the proposed method over the state-of-the-arts.
</div>


**Snapshot Hyperspectral Light Field Imaging** <br>
*Zhiwei Xiong, Lizhi Wang, Huiqun Li, Dong Liu, Feng Wu* <br>
<span><pub>IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2017</pub></span> <br>
[Paper](https://openaccess.thecvf.com/content_cvpr_2017/html/Xiong_Snapshot_Hyperspectral_Light_CVPR_2017_paper){:target="_blank"} |
<a onclick='expandABS("xiong17cvpr")'> Abstract </a>
<div style="display: none;" class=abs id="xiong17cvpr"><br>
This paper presents the first snapshot hyperspectral light field imager in practice. Specifically, we design a novel hybrid camera system to obtain two complementary measurements that sample the angular and spectral dimensions respectively. To recover the full 5D hyperspectral light field from the severely undersampled measurements, we then propose an efficient computational reconstruction algorithm by exploiting the large correlations across the angular and spectral dimensions through self-learned dictionaries. Simulation on an elaborate hyperspectral light field dataset validates the effectiveness of the proposed approach. Hardware experimental results demonstrate that, for the first time to our knowledge, a 5D hyperspectral light field containing 9x9 angular views and 27 spectral bands can be acquired in a single shot.

</div>



---


__[▶ Image](/super-resolution/sr-image){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Video](/super-resolution/sr-video){: style="color: rgb(191, 0, 0)"}__ 
__[▲ Spectrum](/super-resolution/sr-spectrum){: style="color: rgb(191, 0, 0)"}__
__[▶ Light Field](/super-resolution/sr-light-field){: style="color: rgb(191, 0, 0)"}__
