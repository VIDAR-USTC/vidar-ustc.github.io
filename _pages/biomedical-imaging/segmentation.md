---
title: "Research Topic: Biomedical Image Analysis"
excerpt: "Biomedical Image Analysis"
author_profile: True
permalink: /biomedical-imaging/segmentation.html
---


__[▼ Segmentation](/biomedical-imaging/segmentation){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Registration](/biomedical-imaging/registration){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Restoration](/biomedical-imaging/restoration){: style="color: rgb(191, 0, 0)"}__
__[▶ Misc.](/biomedical-imaging/misc){: style="color: rgb(191, 0, 0)"}__



## Segmentation


<span><highlighted>(New!)</highlighted></span> **Learning Cross-Representation Affinity Consistency for Sparsely Supervised Biomedical Instance Segmentation** <br>
*Xiaoyu Liu, Wei Huang, Zhiwei Xiong, Shenglong Zhou, Yueyi Zhang, Xuejin Chen, Zheng-Jun Zha, Feng Wu* <br>
<span><pub>IEEE/CVF International Conference on Computer Vision (ICCV), 2023</pub></span> <br> 
[Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Liu_Learning_Cross-Representation_Affinity_Consistency_for_Sparsely_Supervised_Biomedical_Instance_Segmentation_ICCV_2023_paper.html){:target="_blank"} |
[Code](https://github.com/liuxy1103/CRAC){:target="_blank"} |
<a onclick='expandABS("liu23iccv")'> Abstract </a>
<div style="display: none;" class=abs id="liu23iccv"><br>
Sparse instance-level supervision has recently been explored to address insufficient annotation in biomedical instance segmentation, which is easier to annotate crowded instances and better preserves instance completeness for 3D volumetric datasets compared to common semi-supervision.In this paper, we propose a sparsely supervised biomedical instance segmentation framework via cross-representation affinity consistency regularization. Specifically, we adopt two individual networks to enforce the perturbation consistency between an explicit affinity map and an implicit affinity map to capture both feature-level instance discrimination and pixel-level instance boundary structure. We then select the highly confident region of each affinity map as the pseudo label to supervise the other one for affinity consistency learning. To obtain the highly confident region, we propose a pseudo-label noise filtering scheme by integrating two entropy-based decision strategies. Extensive experiments on four biomedical datasets with sparse instance annotations show the state-of-the-art performance of our proposed framework. For the first time, we demonstrate the superiority of sparse instance-level supervision on 3D volumetric datasets, compared to common semi-supervision under the same annotation cost.
</div>

<span><highlighted>(New!)</highlighted></span> **PCTrans: Position-Guided Transformer with Query Contrast for Biological Instance Segmentation** <br>
*Qi Chen, Wei Huang, Xiaoyu Liu, Jiacheng Li, Zhiwei Xiong* <br>
<span><pub>IEEE International Conference on Computer Vision Workshops (ICCVW), 2023</pub></span> <br>
[Paper](https://openaccess.thecvf.com/content/ICCV2023W/BIC/html/Chen_PCTrans_Position-Guided_Transformer_with_Query_Contrast_for_Biological_Instance_Segmentation_ICCVW_2023_paper.html){:target="_blank"} |
[Code](https://github.com/qic999/PCTrans){:target="_blank"} |
<a onclick='expandABS("chen23iccvw")'> Abstract </a>
<div style="display: none;" class=abs id="chen23iccvw"><br>
Recently, query-based transformer gradually draws attention in segmentation tasks due to its powerful ability. Compared to instance segmentation in natural images, biological instance segmentation is more challenging due to high texture similarity, crowded objects and limited annotations. Therefore, it remains a pending issue to extract meaningful queries to model biological instances. In this paper, we analyze the problem when queries meet biological images and propose a novel Position-guided Transformer with query Contrast (PCTrans) for biological instance segmentation. PCTrans tackles the mentioned issue in two ways. First, for high texture similarity and crowded objects, we incorporate position information to guide query learning and mask prediction. This involves considering position similarity when learning queries and designing a dynamic mask head that takes instance position into account. Second, to learn more discriminative representation of the queries under limited annotated data, we further design two contrastive losses, namely Query Embedding Contrastive (QEC) loss and Mask Candidate Contrastive (MCC) loss. Experiments on two representative biological instance segmentation datasets demonstrate the superiority of PCTrans over existing methods.

</div>


<span><highlighted>(New!)</highlighted></span> **Self-Supervised Neuron Segmentation with Multi-Agent Reinforcement Learning** <br>
*Yinda Chen, Wei Huang, Shenglong Zhou, Qi Chen, Zhiwei Xiong* <br>
<span><pub>International Joint Conference on Artificial Intelligence (IJCAI), 2023</pub></span> <br>
[Paper](https://www.ijcai.org/proceedings/2023/0068.pdf){:target="_blank"} |
[Code](https://github.com/ydchen0806/dbMiM){:target="_blank"} |
<a onclick='expandABS("chen23")'> Abstract </a>
<div style="display: none;" class=abs id="chen23"><br>
The performance of existing supervised neuron segmentation methods is highly dependent on the number of accurate annotations, especially when applied to large scale electron microscopy (EM) data. By extracting semantic information from unlabeled data, self-supervised methods can improve the performance of downstream tasks, among which the mask image model (MIM) has been widely used due to its simplicity and effectiveness in recovering original information from masked images. However, due to the high degree of structural locality in EM images, as well as the existence of considerable noise, many voxels contain little discriminative information, making MIM pretraining inefficient on the neuron segmentation task. To overcome this challenge, we propose a decision-based MIM that utilizes reinforcement learning (RL) to automatically search for optimal image masking ratio and masking strategy. Due to the vast exploration space, using single-agent RL for voxel prediction is impractical. Therefore, we treat each input patch as an agent with a shared behavior policy, allowing for multi-agent collaboration. Furthermore, this multi-agent model can capture dependencies between voxels, which is beneficial for the downstream segmentation task. Experiments conducted on representative EM datasets demonstrate that our approach has a significant advantage over alternative self-supervised methods on the task of neuron segmentation. Code is available at https://github.com/ydchen0806/dbMiM.
</div>


**A Soma Segmentation Benchmark in Full Adult Fly Brain** <br>
*Xiaoyu Liu, Bo Hu, Mingxing Li, Wei Huang, Yueyi Zhang, Zhiwei Xiong* <br>
<span><pub>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2023</pub></span> <br>
[Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Liu_A_Soma_Segmentation_Benchmark_in_Full_Adult_Fly_Brain_CVPR_2023_paper.html){:target="_blank"} |
[Code & Dataset](https://github.com/liuxy1103/EMADS){:target="_blank"} |
[Intro Video](https://www.youtube.com/watch?v=b8AW6a7mjnM){:target="_blank"} |
<a onclick='expandABS("liu23")'> Abstract </a>
<div style="display: none;" class=abs id="liu23"><br>
Neuron reconstruction in a full adult fly brain from high-resolution electron microscopy (EM) data is regarded as a cornerstone for neuroscientists to explore how neurons inspire intelligence. As the central part of neurons, somas in the full brain indicate the origin of neurogenesis and neural functions. However, due to the absence of EM datasets specifically annotated for somas, existing deep learning-based neuron reconstruction methods cannot directly provide accurate soma distribution and morphology. Moreover, full brain neuron reconstruction remains extremely time-consuming due to the unprecedentedly large size of EM data. In this paper, we develop an efficient soma reconstruction method for obtaining accurate soma distribution and morphology information in a full adult fly brain. To this end, we first make a high-resolution EM dataset with fine-grained 3D manual annotations on somas. Relying on this dataset, we propose an efficient, two-stage deep learning algorithm for predicting accurate locations and boundaries of 3D soma instances. Further, we deploy a parallelized, high-throughput data processing pipeline for executing the above algorithm on the full brain. Finally, we provide quantitative and qualitative benchmark comparisons on the testset to validate the superiority of the proposed method, as well as preliminary statistics of the reconstructed somas in the full adult fly brain from the biological perspective. We release our code and dataset at https://github.com/liuxy1103/EMADS.
</div>


**Semi-Supervised Neuron Segmentation via Reinforced Consistency Learning** <br>
*Wei Huang, Chang Chen, Zhiwei Xiong, Yueyi Zhang, Xuejin Chen, Xiaoyan Sun, Feng Wu* <br>
<span><pub>IEEE Transactions on Medical Imaging (T-MI), 2022</pub></span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/9777694){:target="_blank"} |
[Code](https://github.com/weih527/SSNS-Net){:target="_blank"} |
<a onclick='expandABS("huang22tmi")'> Abstract </a>
<div style="display: none;" class=abs id="huang22tmi"><br>
Emerging deep learning-based methods have enabled great progress in automatic neuron segmentation from Electron Microscopy (EM) volumes. However, the success of existing methods is heavily reliant upon a large number of annotations that are often expensive and time-consuming to collect due to dense distributions and complex structures of neurons. If the required quantity of manual annotations for learning cannot be reached, these methods turn out to be fragile. To address this issue, in this article, we propose a two-stage, semi-supervised learning method for neuron segmentation to fully extract useful information from unlabeled data. First, we devise a proxy task to enable network pre-training by reconstructing original volumes from their perturbed counterparts. This pre-training strategy implicitly extracts meaningful information on neuron structures from unlabeled data to facilitate the next stage of learning. Second, we regularize the supervised learning process with the pixel-level prediction consistencies between unlabeled samples and their perturbed counterparts. This improves the generalizability of the learned model to adapt diverse data distributions in EM volumes, especially when the number of labels is limited. Extensive experiments on representative EM datasets demonstrate the superior performance of our reinforced consistency learning compared to supervised learning, i.e., up to 400% gain on the VOI metric with only a few available labels. This is on par with a model trained on ten times the amount of labeled data in a supervised manner. Code is available at https://github.com/weih527/SSNS-Net.

</div>




**Mask Rearranging Data Augmentation for 3D Mitochondria Segmentation** <br>
*Qi Chen, Mingxing Li, Jiacheng Li, Bo Hu, Zhiwei Xiong* <br>
<span><pub>Int. Conf. Medical Image Computing and Computer-Assisted Intervention (MICCAI), 2022</pub></span> <br> 
[Paper](https://link.springer.com/chapter/10.1007/978-3-031-16440-8_4){:target="_blank"} |
[Code](https://github.com/qic999/MRDA_MitoSeg){:target="_blank"} |
<a onclick='expandABS("chen22")'> Abstract </a>
<div style="display: none;" class=abs id="chen22"><br>
3D mitochondria segmentation in electron microscopy (EM) images has achieved significant progress. However, existing learning-based methods with high performance typically rely on extensive training data with high-quality manual annotations, which is time-consuming and labor-intensive. To address this challenge, we propose a novel data augmentation method tailored for 3D mitochondria segmentation. First, we train a Mask2EM network for learning the mapping from the ground-truth instance masks to real 3D EM images in an adversarial manner. Based on the Mask2EM network, we can obtain synthetic 3D EM images from arbitrary instance masks to form a sufficient amount of paired training data for segmentation. Second, we design a 3D mask layout generator to generate diverse instance layouts by rearranging volumetric instance masks according to mitochondrial distance distribution. Experiments demonstrate that, as a plug-and-play module, the proposed method boosts existing 3D mitochondria segmentation networks to achieve state-of-the-art performance. Especially, the proposed method brings significant improvements when training data is extremely limited. Code will be available at: https://github.com/qic999/MRDA_MitoSeg.



</div>


**Efficient Biomedical Instance Segmentation via Knowledge Distillation** <br>
*Xiaoyu Liu, Bo Hu, Wei Huang, Yueyi Zhang, Zhiwei Xiong* <br>
<span><pub>Int. Conf. Medical Image Computing and Computer-Assisted Intervention (MICCAI), 2022</pub></span> <br> 
[Paper](https://link.springer.com/chapter/10.1007/978-3-031-16440-8_2){:target="_blank"} |
[Code](https://github.com/liuxy1103/BISKD){:target="_blank"} |
<a onclick='expandABS("liu22miccai")'> Abstract </a>
<div style="display: none;" class=abs id="liu22miccai"><br>
Biomedical instance segmentation is vulnerable to complicated instance morphology, resulting in over-merge and over-segmentation. Recent advanced methods apply convolutional neural networks to predict pixel embeddings to overcome this problem. However, these methods suffer from heavy computational burdens and massive storage. In this paper, we present the first knowledge distillation method tailored for biomedical instance segmentation to transfer the knowledge from a cumbersome teacher network to a lightweight student one. Different from existing distillation methods on other tasks, we consider three kinds of essential knowledge of the instance segmentation task, i.e., instance-level features, instance relationships in the feature space and pixel-level instance boundaries. Specifically, we devise two distillation schemes: (i) instance graph distillation that transfers the knowledge of instance-level features and instance relationships by the instance graphs built from embeddings of the teacher-student pair, respectively, and (ii) pixel affinity distillation that converts pixel embeddings into pixel affinities and explicitly transfers the structured knowledge of instance boundaries encoded in affinities. Experimental results on a 3D electron microscopy dataset (CREMI) and a 2D plant phenotype dataset (CVPPP) demonstrate that the student models trained through our distillation method use fewer than 1% parameters and less than 10% inference time while achieving promising performance compared with corresponding teacher models. Code is available at https://github.com/liuxy1103/BISKD.



</div>

**Domain Adaptive Mitochondria Segmentation via Enforcing Inter-Section Consistency** <br>
*Wei Huang, Xiaoyu Liu, Zhen Cheng, Yueyi Zhang, Zhiwei Xiong* <br>
<span><pub>Int. Conf. Medical Image Computing and Computer-Assisted Intervention (MICCAI), 2022</pub></span> <br> 
[Paper](https://link.springer.com/chapter/10.1007/978-3-031-16440-8_9){:target="_blank"} |
[Code](https://github.com/weih527/DA-ISC){:target="_blank"} |
<a onclick='expandABS("huang22miccai")'> Abstract </a>
<div style="display: none;" class=abs id="huang22miccai"><br>
Deep learning-based methods for mitochondria segmentation require sufficient annotations on Electron Microscopy (EM) volumes, which are often expensive and time-consuming to collect. Recently, Unsupervised Domain Adaptation (UDA) has been proposed to avoid annotating on target EM volumes by exploiting annotated source EM volumes. However, existing UDA methods for mitochondria segmentation only address the intra-section gap between source and target volumes but ignore the inter-section gap between them, which restricts the generalization capability of the learned model on target volumes. In this paper, for the first time, we propose a domain adaptive mitochondria segmentation method via enforcing inter-section consistency. The key idea is to learn an inter-section residual on the segmentation results of adjacent sections using a CNN. The inter-section residuals predicted from source and target volumes are then aligned via adversarial learning. Meanwhile, guided by the learned inter-section residual, we can generate pseudo labels to supervise the segmentation of adjacent sections inside the target volume, which further enforces inter-section consistency. Extensive experiments demonstrate the superiority of our proposed method on four representative and diverse EM datasets. Code is available at https://github.com/weih527/DA-ISC.

</div>

**Biological Instance Segmentation with a Superpixel-Guided Graph** <br>
*Xiaoyu Liu, Wei Huang, Yueyi Zhang, Zhiwei Xiong* <br>
<span><pub>International Joint Conference on Artificial Intelligence (IJCAI), 2022</pub></span> <br>
[Paper](https://www.ijcai.org/proceedings/2022/0169.pdf){:target="_blank"} |
[Code](https://github.com/liuxy1103/BISSG){:target="_blank"} |
<a onclick='expandABS("liu22ijcai")'> Abstract </a>
<div style="display: none;" class=abs id="liu22ijcai"><br>
Recent advanced proposal-free instance segmentation methods have made significant progress in biological images. However, existing methods are vulnerable to local imaging artifacts and similar object appearances, resulting in over-merge and over-segmentation. To reduce these two kinds of errors, we propose a new biological instance segmentation framework based on a superpixelguided graph, which consists of two stages, ie, superpixel-guided graph construction and superpixel agglomeration. Specifically, the first stage generates enough superpixels as graph nodes to avoid over-merge, and extracts node and edge features to construct an initialized graph. The second stage agglomerates superpixels into instances based on the relationship of graph nodes predicted by a graph neural network (GNN). To solve oversegmentation and prevent introducing additional over-merge, we specially design two loss functions to supervise the GNN, ie, a repulsion-attraction (RA) loss to better distinguish the relationship of nodes in the feature space, and a maximin agglomeration score (MAS) loss to pay more attention to crucial edge classification. Extensive experiments on three representative biological datasets demonstrate the superiority of our method over existing state-of-the-art methods. Code is available at https://github.com/liuxy1103/BISSG.

</div>

**Advanced Deep Networks for 3D Mitochondria Instance Segmentation** <br>
*Mingxing Li, Chang Chen, Xiaoyu Liu, Wei Huang, Yueyi Zhang, Zhiwei Xiong* <br>
<span><pub>IEEE International Symposium on Biomedical Imaging (ISBI), 2022</pub></span> <br> 
<span><highlighted>Winner</highlighted> of ISBI 2021 Challenge on Large-scale 3D Mitochondria Instance Segmentation<span> <br>
[Paper](https://ieeexplore.ieee.org/abstract/document/9761477){:target="_blank"} |
[Code](https://github.com/Limingxing00/MitoEM2021-Challenge){:target="_blank"} |
<a onclick='expandABS("li22isbi")'> Abstract </a>
<div style="display: none;" class=abs id="li22isbi"><br>
Mitochondria instance segmentation from electron microscopy (EM) images has seen notable progress since the introduction of deep learning methods. In this paper, we propose two advanced deep networks, named Res-UNet-R and Res-UNet-H, for 3D mitochondria instance segmentation from Rat and Human samples. Specifically, we design a simple yet effective anisotropic convolution block and deploy a multi-scale training strategy, which together boost the segmentation performance. Moreover, we enhance the generalizability of the trained models on the test set by adding a denoising operation as pre-processing. In the Large-scale 3D Mitochondria Instance Segmentation Challenge at ISBI 2021, our method ranks the 1st place. Code is available at https://github.com/Limingxing00/MitoEM2021-Challenge.

</div>


**Learning to Model Pixel-Embedded Affinity for Homogeneous Instance Segmentation** <br>
*Wei Huang, Shiyu Deng, Chang Chen, Xueyang Fu, Zhiwei Xiong* <br>
<span><pub>AAAI Conference on Artificial Intelligence (AAAI), 2022</pub></span> <br> 
[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/19984){:target="_blank"} |
[Code](https://github.com/weih527/Pixel-Embedded-Affinity){:target="_blank"} |
<a onclick='expandABS("huang22aaai")'> Abstract </a>
<div style="display: none;" class=abs id="huang22aaai"><br>
Homogeneous instance segmentation aims to identify each instance in an image where all interested instances belong to the same category, such as plant leaves and microscopic cells. Recently, proposal-free methods, which straightforwardly generate instance-aware information to group pixels into different instances, have received increasing attention due to their efficient pipeline. However, they often fail to distinguish adjacent instances due to similar appearances, dense distribution and ambiguous boundaries of instances in homogeneous images. In this paper, we propose a pixel-embedded affinity modeling method for homogeneous instance segmentation, which is able to preserve the semantic information of instances and improve the distinguishability of adjacent instances. Instead of predicting affinity directly, we propose a self-correlation module to explicitly model the pairwise relationships between pixels, by estimating the similarity between embeddings generated from the input image through CNNs. Based on the self-correlation module, we further design a cross-correlation module to maintain the semantic consistency between instances. Specifically, we map the transformed input images with different views and appearances into the same embedding space, and then mutually estimate the pairwise relationships of embeddings generated from the original input and its transformed variants. In addition, to integrate the global instance information, we introduce an embedding pyramid module to model affinity on different scales. Extensive experiments demonstrate the versatile and superior performance of our method on three representative datasets. Code and models are available at https://github.com/weih527/Pixel-Embedded-Affinity.


</div>


**Towards Neuron Segmentation from Macaque Brain Images: A Weakly Supervised Approach** <br>
*Meng Dong, Dong Liu, Zhiwei Xiong, Xuejin Chen, Yueyi Zhang, Zheng-Jun Zha, Guoqiang Bi, Feng Wu* <br>
<span><pub>Int. Conf. Medical Image Computing and Computer-Assisted Intervention (MICCAI), 2020</pub></span> <br> 
[Paper](https://link.springer.com/chapter/10.1007/978-3-030-59722-1_19){:target="_blank"} |
[Code](https://github.com/MeowMeowLady/Towards-Neuron-Seg-Macaque-Brain){:target="_blank"} |
[Dataset](https://braindata.bitahub.com/Macaque_Brain_Segmentation.html){:target="_blank"} |
<a onclick='expandABS("dong20")'> Abstract </a>
<div style="display: none;" class=abs id="dong20"><br>
The advance of microscopic imaging technology has enabled the observation of primate brain in its entirety and at single-neuron resolution. It is then an urgent need to develop means for automated analyses of these brain images, e.g. neuron segmentation. Deep learning is demonstrated an appealing approach for segmentation of natural images, but the success of deep learning is highly dependent on the large-scale and well-built training data that are costly to collect. In this paper, we take a step towards the goal of neuron segmentation from primate brain images, using a weakly supervised approach. We build – to our best knowledge – the first dual-channel three-dimensional image dataset of macaque brain for neuron segmentation. We propose two kinds of “weak” labels, i.e. central points and rough masks, to prepare training data with an affordable cost. Accordingly, we design a weakly supervised learning method for neuron instance segmentation where instances can be easily extracted from the predicted peak-shape probability maps. Experimental results have shown the effectiveness of our approach. We also verify the efficiency of the proposed method on a public nuclei dataset. Our dataset and code have been published at https://braindata.bitahub.com/.

</div>


**Instance Segmentation from Volumetric Biomedical Images Without Voxel-Wise Labeling** <br>
*Meng Dong, Dong Liu, Zhiwei Xiong, Xuejin Chen, Yueyi Zhang, Zheng-Jun Zha, Guoqiang Bi, Feng Wu* <br>
<span><pub>Int. Conf. Medical Image Computing and Computer-Assisted Intervention (MICCAI), 2019</pub></span> <br> 
[Paper](https://link.springer.com/chapter/10.1007/978-3-030-32245-8_10){:target="_blank"} |
[Code](https://github.com/MeowMeowLady/InstanceSeg-Without-Voxelwise-Labeling){:target="_blank"} |
[Dataset](https://braindata.bitahub.com/Soma_segmentation.html){:target="_blank"} |
<a onclick='expandABS("dong19")'> Abstract </a>
<div style="display: none;" class=abs id="dong19"><br>
Volumetric instance segmentation plays a significant role in biomedical morphological analyses. The improvement of segmentation accuracy has been accelerated by the progress of deep learning-based methods. However, such methods usually rely heavily on plenty of precise annotation, which is time-consuming and may need some expert knowledge to label manually. Although there are several studies focusing on weakly supervised methods in order to save the labeling cost, previous approaches still more or less require voxel-wise annotation. In this paper, we propose a weakly supervised instance segmentation method that needs no voxel-wise labeling. Our approach takes advantage of two advanced techniques: one is the popular proposal-based framework (Faster R-CNN in this paper) for instance detection, and the other is the peak response mapping (PRM) for finding visual cues of instances. Then a new thresholding method combines detected boxes and visual cues to generate final instance segmentation results. We conduct experiments on two biomedical datasets, one of which is a large-scale mouse brain dataset at single-neuron resolution collected by ourselves. Results on both datasets validate the effectiveness of our proposed method.

</div>


---


__[▲ Segmentation](/biomedical-imaging/segmentation){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Registration](/biomedical-imaging/registration){: style="color: rgb(191, 0, 0)"}__ 
__[▶ Restoration](/biomedical-imaging/restoration){: style="color: rgb(191, 0, 0)"}__
__[▶ Misc.](/biomedical-imaging/misc){: style="color: rgb(191, 0, 0)"}__
