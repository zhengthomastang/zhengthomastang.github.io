---
title: "Multiple-Kernel Based Vehicle Tracking Using 3D Deformable Model and Camera Self-Calibration"
collection: publications
permalink: /publication/AIC17MultiKernelTrack
date: 2017-08-05
venue: "2017 IEEE Smart World Congress - 1st AI City Challenge Workshop"
paperurl: "https://arxiv.org/abs/1708.06831"
citation: '<b>Zheng Tang</b>, Gaoang Wang, Tao Liu, Young-Gun Lee, Adwin Jahn, Xu Liu, Xiaodong He and Jenq-Neng Hwang. "Multiple-Kernel Based Vehicle Tracking Using 3D Deformable Model and Camera Self-Calibration". <i>arXiv:1708.06831</i>. 2017.'
---
# Multiple-Kernel Based Vehicle Tracking Using 3D Deformable Model and Camera Self-Calibration

[<a href="https://arxiv.org/abs/1708.06831">Paper</a>]
[<a href="http://zhengthomastang.github.io/files/AIC17MultiKernelTrack_slides.pdf">Slides</a>]
[<a href="https://youtu.be/QA0Iek4tR0k">Demo</a>]

## Abstract
Tracking of multiple objects is an important application in AI City geared towards solving salient problems related to safety and congestion in an urban environment. Frequent occlusion in traffic surveillance has been a major problem in this research field. In this challenge, we propose a model-based vehicle localization method, which builds a kernel at each patch of the 3D deformable vehicle model and associates them with constraints in 3D space. The proposed method utilizes shape fitness evaluation besides color information to track vehicle objects robustly and efficiently. To build 3D car models in a fully unsupervised manner, we also implement evolutionary camera self-calibration from tracking of walking humans to automatically compute camera parameters. Additionally, the segmented foreground masks which are crucial to 3D modeling and camera self-calibration are adaptively refined by multiple-kernel feedback from tracking. For object detection/classification, the state-of-the-art single shot multibox detector (SSD) is adopted to train and test on the NVIDIA AI City Dataset. To improve the accuracy on categories with only few objects, like bus, bicycle and motorcycle, we also employ the pretrained model from YOLO9000 with multi-scale testing. We combine the results from SSD and YOLO9000 based on ensemble learning. Experiments show that our proposed tracking system outperforms both state-of-the-art of tracking by segmentation and tracking by detection.


## Honor
* Winner of Track 2 (AI City Applications) at the 1st AI City Challenge Workshop in SmartWorld 2017
<p align="center">
  <img src="http://zhengthomastang.github.io/images/AIC17MultiKernelTrack_award.png?raw=true" alt="Award" style="width: 450px;"/>
</p>
<p align="center">
  <img src="http://zhengthomastang.github.io/images/AIC17MultiKernelTrack_photo.png?raw=true" alt="Photo" style="width: 450px;"/> 
</p>


## Citation
@misc{Tang17AIC17MultiKernelTrack,  
author = {Zheng Tang and Gaoang Wang and Tao Liu and Young-Gun Lee and Adwin Jahn and Xu Liu and Xiaodong He and Jenq-Neng Hwang},  
title = {Multiple-kernel based vehicle tracking using {3D} deformable model and camera self-calibration},  
howpublished = {arXiv:1708.06831},  
year = {2017}  
}
