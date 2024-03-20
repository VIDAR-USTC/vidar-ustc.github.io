---
title: "Research Topic: 3D & Event"
excerpt: "3D & Event"
author_profile: True
permalink: /3D-event/event.html
---



__[▶ Active 3D](/3D-event/active3d){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Passive 3D](/3D-event/passive3d){: style="color: rgb(191, 0, 0)"}__ 
__[▼ Event](/3D-event/event){: style="color: rgb(191, 0, 0)"}__
__[▶ Point Cloud](/3D-event/point-cloud){: style="color: rgb(191, 0, 0)"}__

## Event

<span><highlighted>(New!)</highlighted></span> **Depth From Asymmetric Frame-Event Stereo: A Divide-and-Conquer Approach** <br>
*Xihao Chen, Wenming Weng, Yueyi Zhang, Zhiwei Xiong* <br>
<span><pub>IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2024</pub></span> <br> 
[Paper](https://openaccess.thecvf.com/content/WACV2024/html/Chen_Depth_From_Asymmetric_Frame-Event_Stereo_A_Divide-and-Conquer_Approach_WACV_2024_paper.html){:target="_blank"} |
[Code](https://github.com/xhchen10/DC-FEStereo){:target="_blank"} |
<a onclick='expandABS("chen24")'> Abstract </a>
<div style="display: none;" class=abs id="chen24"><br>
Event cameras asynchronously measure brightness changes in a scene without motion blur or saturation, while frame cameras capture images with dense intensity and fine details at a fixed rate. The exclusive advantages of the two modalities make depth estimation from Stereo Asymmetric Frame-Event (SAFE) systems appealing. However, due to the inevitable information absence of one modality in certain challenging regions, existing stereo matching methods lose efficacy for asymmetric inputs from SAFE systems. In this paper, we propose a divide-and-conquer approach that decomposes depth estimation from SAFE systems into three sub-tasks, i.e., frame-event stereo matching, frame-based Structure-from-Motion (SfM), and event-based SfM. In this way, the above challenging regions are addressed by monocular SfM, which estimates robust depth with two views belonging to the same functioning modality. Moreover, we propose a dual sampling strategy to construct cost volumes with identical spatial locations and depth hypotheses for different sub-tasks, which enables sub-task fusion at the cost volume level. To tackle the occlusion issue raised by the sampling strategy, we further introduce a temporal fusion scheme to utilize long-term sequential inputs with multi-view information. Experimental results validate the superior performance of our method over existing solutions.
</div>

<span><highlighted>(New!)</highlighted></span> **Fast 3D Reconstruction via Event-based Structured Light with Spatio-temporal Coding** <br>
*Jiacheng Fu, Yueyi Zhang, Yue Li, Jiacheng Li, Zhiwei Xiong* <br>
<span><pub>Optics Express (OE), 2023</pub></span> <br> 
[Paper](https://opg.optica.org/oe/fulltext.cfm?uri=oe-31-26-44588){:target="_blank"} |
[Demo Video](https://opg.optica.org/oe/viewmedia.cfm?uri=oe-31-26-44588&seq=v001){:target="_blank"} |
<a onclick='expandABS("Fu23")'> Abstract </a>
<div style="display: none;" class=abs id="Fu23"><br>
Event-based structured light (SL) systems leverage bio-inspired event cameras, which are renowned for their low latency and high dynamics, to drive progress in high-speed structured light systems. However, existing event-based structured light methods concentrate on the independent construction of either time-domain or space-domain features for stereo matching, ignoring the spatio-temporal consistency towards depth. In this work, we build an event-based SL system that consists of a laser point projector and an event camera, and we devise a spatial-temporal coding strategy that realizes depth encoding in dual domains through a single shot. To exploit the spatio-temporal synergy, we further present STEM, a novel Spatio-Temporal Enhanced Matching approach for 3D reconstruction. STEM is comprised of two parts, the spatio-temporal enhancing (STE) algorithm and the spatio-temporal matching (STM) algorithm. Specifically, STE integrates the dual-domain information to increase the saliency of the temporal coding, providing a more robust basis for matching. STM is a stereo matching algorithm explicitly tailored to the unique characteristics of event data modality, which computes the disparity via a meticulously designed hybrid cost function. Experimental results demonstrate the superior performance of our proposed method, achieving a reconstruction rate of 16 fps and a low root mean square error of 0.56 mm at a distance of 0.72 m.

</div>


**Unsupervised Video Deraining with An Event Camera** <br>
*Jin Wang, Wenming Weng, Yueyi Zhang, Zhiwei Xiong* <br>
<span><pub>IEEE/CVF International Conference on Computer Vision (ICCV), 2023</pub></span> <br> 
[Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Wang_Unsupervised_Video_Deraining_with_An_Event_Camera_ICCV_2023_paper.html){:target="_blank"} |
[Code](https://github.com/booker-max/Unsupervised-Deraining-with-Event-Camera){:target="_blank"} |
<a onclick='expandABS("wang23")'> Abstract </a>
<div style="display: none;" class=abs id="wang23"><br>
Current unsupervised video deraining methods are inefficient in modeling the intricate spatio-temporal properties of rain, which leads to unsatisfactory results. In this paper, we propose a novel approach by integrating a bio-inspired event camera into the unsupervised video deraining pipeline, which enables us to capture high temporal resolution information and model complex rain characteristics. Specifically, we first design an end-to-end learning-based network consisting of two modules, the asymmetric separation module and the cross-modal fusion module. The two modules are responsible for segregating the features of the rain-background layer, and for positive enhancement and negative suppression from a cross-modal perspective, respectively. Second, to regularize the network training, we elaborately design a cross-modal contrastive learning method that leverages the complementary information from event cameras, exploring the mutual exclusion and similarity of rain-background layers in different domains. This encourages the deraining network to focus on the distinctive characteristics of each layer and learn a more discriminative representation. Moreover, we construct the first real-world dataset comprising rainy videos and events using a hybrid imaging system. Extensive experiments demonstrate the superior performance of our method on both synthetic and real-world datasets.
</div>

**Event-Based Blurry Frame Interpolation Under Blind Exposure** <br>
*Wenming Weng, Yueyi Zhang, Zhiwei Xiong* <br>
<span><pub>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2023</pub></span> <br>
[Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Weng_Event-Based_Blurry_Frame_Interpolation_Under_Blind_Exposure_CVPR_2023_paper.html){:target="_blank"} |
[Code](https://github.com/WarranWeng/EBFI-BE){:target="_blank"} |
[Intro Video](https://www.youtube.com/watch?v=n3LrH5DS2yA){:target="_blank"} |
<a onclick='expandABS("weng23")'> Abstract </a>
<div style="display: none;" class=abs id="weng23"><br>
Restoring sharp high frame-rate videos from low frame-rate blurry videos is a challenging problem. Existing blurry frame interpolation methods assume a predefined and known exposure time, which suffer from severe performance drop when applied to videos captured in the wild. In this paper, we study the problem of blurry frame interpolation under blind exposure with the assistance of an event camera. The high temporal resolution of the event camera is beneficial to obtain the exposure prior that is lost during the imaging process. Besides, sharp frames can be restored using event streams and blurry frames relying on the mutual constraint among them. Therefore, we first propose an exposure estimation strategy guided by event streams to estimate the lost exposure prior, transforming the blind exposure problem well-posed. Second, we propose to model the mutual constraint with a temporal-exposure control strategy through iterative residual learning. Our blurry frame interpolation method achieves a distinct performance boost over existing methods on both synthetic and self-collected real-world datasets under blind exposure.
</div>



**Progressive Spatio-Temporal Alignment for Efficient Event-Based Motion Estimation** <br>
*Xueyan Huang, Yueyi Zhang, Zhiwei Xiong* <br>
<span><pub>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2023</pub></span> <br>
[Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Huang_Progressive_Spatio-Temporal_Alignment_for_Efficient_Event-Based_Motion_Estimation_CVPR_2023_paper.html){:target="_blank"} |
[Code](https://github.com/huangxueyan/PEME){:target="_blank"} |
[Intro Video](https://www.youtube.com/watch?v=hEMm-Fkim7M){:target="_blank"} |
<a onclick='expandABS("huang23")'> Abstract </a>
<div style="display: none;" class=abs id="huang23"><br>
In this paper, we propose an efficient event-based motion estimation framework for various motion models. Different from previous works, we design a progressive event-to-map alignment scheme and utilize the spatio-temporal correlations to align events. In detail, we progressively align sampled events in an event batch to the time-surface map and obtain the updated motion model by minimizing a novel time-surface loss. In addition, a dynamic batch size strategy is applied to adaptively adjust the batch size so that all events in the batch are consistent with the current motion model. Our framework has three advantages: a) the progressive scheme refines motion parameters iteratively, achieving accurate motion estimation; b) within one iteration, only a small portion of events are involved in optimization, which greatly reduces the total runtime; c) the dynamic batch size strategy ensures that the constant velocity assumption always holds. We conduct comprehensive experiments to evaluate our framework on challenging high-speed scenes with three motion models: rotational, homography, and 6-DOF models. Experimental results demonstrate that our framework achieves state-of-the-art estimation accuracy and efficiency.

</div>


**EVA$^{2}$: Event-Assisted Video Frame Interpolation via Cross-Modal Alignment and Aggregation** <br>
*Zeyu Xiao, Wenming Weng, Yueyi Zhang, Zhiwei Xiong* <br>
<span><pub>IEEE Transactions on Computational Imaging (T-CI), 2022</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/document/9982428/){:target="_blank"} |
[Code](https://github.com/zeyuxiao1997/EVA2){:target="_blank"} |
<a onclick='expandABS("xiao22")'> Abstract </a>
<div style="display: none;" class=abs id="xiao22"><br>
We consider the problem of event-assisted video frame interpolation (VFI), a new track for VFI, by introducing the event data, a novel sensing modality, into the process of generating intermediate frames from low-frame-rate videos. This new track challenges existing methods in two aspects: (1) how to utilize the event data to align boundary keyframes to intermediate ones, especially when there are corruptions in scenes ( e.g. , non-uniform motion, object occlusions, and illumination changes); (2) how to effectively utilize and aggregate cross-modal information for further mitigating corruptions and refining details. In this paper, we propose a novel E vent-assisted V FI method with cross-modal A lignment and A ggregation, termed EVA$^{2}$, to address these challenges. First, to handle corruptions during alignment, we devise the cross-modal Event-Guided Alignment (EGA) module, in which the intermediate frames are aligned at both the feature and the image levels. The alignment operation in the EGA module is guided by the offset maps generated from the event data and information extracted from the input boundary keyframes. Second, we propose the cross-modal Event-aware Dynamic Aggregation (EDA) module, in which the event-aware dynamic convolution operation is applied to aggregate the event data with the aligned results adaptively for further improvements. Extensive experiments on both synthetic and real-world datasets validate the effectiveness of our EVA$^{2}$.
</div>


**Boosting Event Stream Super-Resolution with a Recurrent Neural Network** <br>
*Wenming Weng, Yueyi Zhang, Zhiwei Xiong* <br>
<span><pub>European Conference on Computer Vision (ECCV), 2022</pub></span> <br>
[Paper](https://link.springer.com/chapter/10.1007/978-3-031-20068-7_27){:target="_blank"} |
[Code](https://github.com/WarranWeng/ESR){:target="_blank"} |
<a onclick='expandABS("weng22")'> Abstract </a>
<div style="display: none;" class=abs id="weng22"><br>
Existing methods for event stream super-resolution (SR) either require high-quality and high-resolution frames or underperform for large factor SR. To address these problems, we propose a recurrent neural network for event SR without frames. First, we design a temporal propagation net for incorporating neighboring and long-range event-aware contexts that facilitates event SR. Second, we build a spatiotemporal fusion net for reliably aggregating the spatiotemporal clues of event stream. These two elaborate components are tightly synergized for achieving satisfying event SR results even for 16×
 SR. Synthetic and real-world experimental results demonstrate the clear superiority of our method. Furthermore, we evaluate our method on two downstream event-driven applications, i.e., object recognition and video reconstruction, achieving remarkable performance boost over existing methods.
 </div>



**High-Speed Structured Light Based 3D Scanning Using an Event Camera** <br>
*Xueyan Huang, Yueyi Zhang, Zhiwei Xiong* <br>
<span><pub>Optics Express (OE), 2021</pub></span> <br> 
[Paper](https://opg.optica.org/oe/fulltext.cfm?uri=oe-29-22-35864&id=460651){:target="_blank"} |
[Demo Video](https://opg.optica.org/oe/viewmedia.cfm?uri=oe-29-22-35864&seq=v001){:target="_blank"} |
<a onclick='expandABS("huang21")'> Abstract </a>
<div style="display: none;" class=abs id="huang21"><br>
For a structured light system, scan speed and reconstruction accuracy are usually compromised for limited sensor bandwidth. The bio-inspired camera, also known as the event camera, has high temporal resolution and redundancy-suppressing properties, showing potential to be utilized in a high-speed structured light system. In this paper, we present an event-based structured light system for high-speed 3D scanning, which is composed of an event camera (CeleX-V) and a high-speed digital light projector (TI-DLP6500). The events are triggered by blinking a single pseudo-random pattern by controlling the projector. A simple yet effective algorithm is proposed to generate the event frames from the event stream, and a digital image correlation method is then performed to calculate the displacements, deriving the 3D surfaces of the target objects. A prototype of our proposed system is built with off-the-shelf devices and tested in both static and dynamic scenes. Experiments verify that the proposed system successfully achieves up to a 1000 fps scan rate with an accuracy of 0.27 mm at a distance of 90 cm.


</div>




**Event-Based Video Reconstruction Using Transformer** <br>
*Wenming Weng, Yueyi Zhang, Zhiwei Xiong* <br>
<span><pub>IEEE/CVF International Conference on Computer Vision (ICCV), 2021</pub></span> <br> 
[Paper](https://openaccess.thecvf.com/content/ICCV2021/html/Weng_Event-Based_Video_Reconstruction_Using_Transformer_ICCV_2021_paper){:target="_blank"} |
[Code](https://github.com/WarranWeng/ET-Net){:target="_blank"} |
[Intro Video](https://drive.google.com/file/d/1dSpknMfZrsr1oG7_t36ZkQNhZW0jxZZ8/view?usp=drive_link){:target="_blank"} |
<a onclick='expandABS("weng21")'> Abstract </a>
<div style="display: none;" class=abs id="weng21"><br>
Event cameras, which output events by detecting spatio-temporal brightness changes, bring a novel paradigm to image sensors with high dynamic range and low latency. Previous works have achieved impressive performances on event-based video reconstruction by introducing convolutional neural networks (CNNs). However, intrinsic locality of convolutional operations is not capable of modeling long-range dependency, which is crucial to many vision tasks. In this paper, we present a hybrid CNN-Transformer network for event-based video reconstruction (ET-Net), which merits the fine local information from CNN and global contexts from Transformer. In addition, we further propose a Token Pyramid Aggregation strategy to implement multi-scale token integration for relating internal and intersected semantic concepts in the token-space. Experimental results demonstrate that our proposed method achieves superior performance over state-of-the-art methods on multiple real-world event datasets. The code is available at https://github.com/WarranWeng/ET-Net.
</div>


---



__[▶ Active 3D](/3D-event/active3d){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Passive 3D](/3D-event/passive3d){: style="color: rgb(191, 0, 0)"}__ 
__[▲ Event](/3D-event/event){: style="color: rgb(191, 0, 0)"}__
__[▶ Point Cloud](/3D-event/point-cloud){: style="color: rgb(191, 0, 0)"}__
