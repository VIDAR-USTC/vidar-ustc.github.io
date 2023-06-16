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
