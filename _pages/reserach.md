---
layout: archive
title: "Research Highlights"
permalink: /research/
author_profile: true
---


<style>
firstauthor { color: gray; font-weight: bold; font-size: 0.8em}
author { color: gray; font-size: 0.8em}
venue { color: gray; font-size: 0.8em}
</style>


------

> **Online Map Vectorization for Autonomous Driving: A Rasterization Perspective**
>
> <img src="/images/MapVR1.jpg" alt="MapVR1" width="512"/>
>
> <img src="/images/MapVR2.jpg" alt="MapVR2" width="512"/>
>
> **TL;DR**&emsp; Rasterization can offer complementary benefits to map vectorization. Motivated by this, we propose (i) MapVR, a precise map vectorization framework bridging map rasterization and map vectorization, and (ii) a highly sensitive rasterization-based metric for map vectorization.
>
> <firstauthor>Gongjie Zhang</firstauthor><author>, Jiahao Lin, Shuang Wu, Yilin Song, Zhipeng Luo, Yang Xue, Shijian Lu, and Zuoguan Wang</author><venue><br>The Thirty-seventh Annual Conference on Neural Information Processing Systems (NeurIPS), 2023</venue>

---

> **Towards Efficient Use of Multi-Scale Features in Transformer-Based Object Detectors**
>
> <img src="/images/IMFA.jpg" alt="IMFA" width="512"/>
>
> **TL;DR**&emsp; This paper presents IMFA (Iterative Multi-scale Feature Aggregation) -- the first generic paradigm to efficiently leverage multi-scale features in Transformer-based object detectors (e.g., DETR, Anchor-DETR, etc.). For efficiency, IMFA only samples multi-scale features from a few crucial keypoints within a few promising regions. We demonstrate on multiple detectors that even such extremely sparse multi-scale features are still highly beneficial to detection accuracy at small computational overheads.
>
> <firstauthor>Gongjie Zhang</firstauthor><author>, Zhipeng Luo, Zichen Tian, Jingyi Zhang, Xiaoqin Zhang, and Shijian Lu</author><venue><br>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2023</venue>

---

> **Meta-DETR: Image-Level Few-Shot Detection with Inter-Class Correlation Exploitation**
>
> <img src="/images/MetaDETR1.jpg" alt="MetaDETR1" width="500"/>
>
> <img src="/images/MetaDETR2.jpg" alt="MetaDETR2" width="500"/>
>
> **TL;DR**&emsp; Meta-DETR is a state-of-the-art few-shot object detector that performs image-level meta-learning-based prediction and effectively exploits the inter-class correlation to enhance generalization from old knowledge to new classes. Meta-DETR entirely bypasses the proposal quality gap between base and novel classes, thus achieving superior performance than R-CNN-based few-shot object detectors. In addition, Meta-DETR performs meta-learning on a set of support classes at one go, thus effectively leveraging the inter-class correlation for better generalization.
>
> <firstauthor>Gongjie Zhang</firstauthor><author>, Zhipeng Luo, Kaiwen Cui, Shijian Lu, and Eric P. Xing</author><venue><br>IEEE Transactions on Pattern Analysis and Machine Intelligence (T-PAMI), 2022</venue>
>
> [\[Blog(By others)\]](https://towardsdatascience.com/review-on-few-shot-object-detection-185965e0e6a2)  [\[中文解读\]](https://cloud.tencent.com/developer/article/1821518)

---

> **Semantic-Aligned Matching for Enhanced DETR Convergence and Multi-Scale Feature Fusion**
>
> <img src="/images/SAM-DETR++.jpg" alt="SAM-DETR++" width="500"/>
>
> **TL;DR**&emsp; This paper presents SAM-DETR++, which is an extension of SAM-DETR. It further extends the semantics-aligned matching mechanism to fuse multi-scale features that are inherently unaligned in semantics, and achieves even faster convergence and superior detection accuracy.
>
> <firstauthor>Gongjie Zhang</firstauthor><author>, Zhipeng Luo, Jiaxing Huang, Shijian Lu, and Eric P. Xing</author><venue><br>International Journal of Computer Vision (IJCV), 2024</venue>


---

> **Accelerating DETR Convergence via Semantic-Aligned Matching**
>
> <img src="/images/SAM-DETR.jpg" alt="SAM-DETR" width="600"/>
>
> **TL;DR**&emsp; This paper presents SAM-DETR -- an efficient DETR-like object detector that can converge within 12 epochs and outperform the strong Faster R-CNN (w/ FPN) baseline on the COCO benchmark. This paper proposes the semantic-aligned matching mechanism to accelerate DETR's training convergence.
>
> <firstauthor>Gongjie Zhang</firstauthor><author>, Zhipeng Luo, Yingchen Yu, Kaiwen Cui, and Shijian Lu</author><venue><br>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2022</venue>
>
> [\[中文论文解读\]](https://zhuanlan.zhihu.com/p/489839282)  [\[中文代码解读（转）\]](https://blog.csdn.net/weixin_43702653/article/details/126404646)
>
> NOTE: Meta-DETR first appeared as a tech report on arXiv.org [\[1st version\]](/files/2103.11731v2.pdf) [\[2nd version\]](/files/2103.11731v3.pdf). Since its release, we have made substantial improvements to the original versions. We recommend to read [the final published version accepted by IEEE Transactions on Pattern Analysis and Machine Intelligence (T-PAMI) in 2022](https://doi.org/10.1109/TPAMI.2022.3195735).

---

> **Defect-GAN: High-Fidelity Defect Synthesis for Automated Defect Inspection**
>
> <img src="/images/DefectGAN.jpg" alt="Defect-GAN" width="500"/>
>
> <img src="/images/DefectGAN2.jpg" alt="Defect-GAN2" width="500"/>
>
> **TL;DR**&emsp; Defect samples are usually rare and expensive to label. This paper presents Defect-GAN to perform high-fidelity defect synthesis with many normal samples and a limited number of defect samples. We show that synthesized defect samples can be effectively leveraged to boost inspection accuracy. The technique is patent-protected and is being used in real scenarios.
>  
> <firstauthor>Gongjie Zhang</firstauthor><author>, Kaiwen Cui, Tzu-Yi Hung, and Shijian Lu</author><venue><br>IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2021</venue>

---

> **PNPDet: Efficient Few-Shot Detection Without Forgetting via Plug-and-Play Sub-Networks**
>
> <img src="/images/PNPDet.jpg" alt="PNPDet" width="500"/>
>
> **TL;DR**&emsp; This paper presents a fine-tuning-based few-shot object detector that learns new concepts without forgetting learned visual concepts via weight normalized sub-networks.
>  
> <firstauthor>Gongjie Zhang</firstauthor><author>, Kaiwen Cui, Rongliang Wu, Shijian Lu, and Yonghong Tian</author><venue><br>IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2021</venue>

---

> **Cascade EF-GAN: Progressive Facial Expression Editing with Local Focuses**
>
> <img src="/images/CascadeEFGAN.jpg" alt="CascadeEF-GAN" width="600"/>
>
> **TL;DR**&emsp; We achieve realistic and vivid facial expression editing by designing separate branches focusing on certain areas (e.g., eyes, noses, etc.), and perform the expression transformation in an iterative manner.
>  
> <author>Rongliang Wu, </author><firstauthor>Gongjie Zhang</firstauthor><author>, Shijian Lu, and Tao Chen</author><venue><br>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) (Oral), 2020</venue>

---

> **CAD-Net: A Context-Aware Detection Network for Objects in Remote Sensing Imagery**
>
> <img src="/images/CAD-Net.jpg" alt="CAD-Net" width="500"/>
>
> **TL;DR**&emsp; One of the earliest works to apply Faster R-CNN to rotated object detection in remote sensing images. The proposed CAD-Net effectively uses multi-level contextual information for robust object detection for satellite imagery.
>  
> <firstauthor>Gongjie Zhang</firstauthor><author>, Shijian Lu, and Wei Zhang</author><venue><br>IEEE Transactions on Geoscience and Remote Sensing (T-GRS), vol.57, no.12, 2019</venue>


---