---
title: "Multiple-Kernel Adaptive Segmentation and Tracking (MAST) for Robust Object Tracking"
collection: publications
permalink: /publication/MAST
<!-- excerpt: 'This paper is about the number 1. The number 2 is left for future work.' -->
date: 2015-12-21
venue: "2016 IEEE International Conference on Acoustics, Speech and Signal Processing"
paperurl: "http://ieeexplore.ieee.org/document/7471849"
citation: '<b>Zheng Tang</b>, Jenq-Neng Hwang, Yen-Shuo Lin and Jen-Hui Chuang. "Multiple-Kernel Adaptive Segmentation and Tracking (MAST) for Robust Object Tracking". <i>Proceedings of 2016 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP 2016)</i>. pp. 3064-3068. 2016.'
---
## Abstract
In a video surveillance system with static cameras, object segmentation often fails when part of the object has similar color with the background, resulting in poor performance of the subsequent object tracking. Multiple kernels have been utilized in object tracking to deal with occlusion, but the performance still highly depends on segmentation. This paper presents an innovative system, named Multiple-kernel Adaptive Segmentation and Tracking (MAST), which dynamically controls the decision thresholds of background subtraction and shadow removal around the adaptive kernel regions based on the preliminary tracking results. Then the objects are tracked for the second time according to the adaptively segmented foreground. Evaluations of both segmentation and tracking on benchmark datasets and our own recorded video sequences demonstrate that the proposed method can successfully track objects in similar-color background and/or shadow areas with favorable segmentation performance.


## Citation
@inproceedings{Tang16MAST,  
author = {Zheng Tang and Jenq-Neng Hwang and Yen-Shuo Lin and Jen-Hui Chuang},  
title = {Multiple-kernel adaptive segmentation and tracking ({MAST}) for robust object tracking},  
booktitle = {Proc. ICASSP},  
pages = {1115--1119},  
address = {Shanghai, China},  
year = {2016}  
}