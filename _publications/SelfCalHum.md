---
title: "Camera Self-Calibration from Tracking of Moving Persons"
collection: publications
permalink: /publication/SelfCalHum
<!-- excerpt: 'This paper is about the number 1. The number 2 is left for future work.' -->
date: 2016-12-04
venue: "2016 International Conference on Pattern Recognition"
paperurl: "https://ieeexplore.ieee.org/document/7899644"
citation: '<b>Zheng Tang</b>, Yen-Shuo Lin, Kuan-Hui Lee, Jenq-Neng Hwang, Jen-Hui Chuang and Zhijun Fang. "Camera Self-Calibration from Tracking of Moving Persons". <i>Proceedings of 2016 International Conference on Pattern Recognition (ICPR 2016)</i>. pp. 260-265. 2016.'
---
# Camera Self-Calibration from Tracking of Moving Persons

[<a href="https://ieeexplore.ieee.org/document/7899644">Paper</a>]
[<a href="http://zhengthomastang.github.io/files/SelfCalHum_slides.pdf">Slides</a>]
[<a href="https://youtu.be/Lqe8AgCxiRg">Demo</a>]


## Abstract
In a video surveillance system with a single static camera, tracking results of moving persons can be effectively used for camera self-calibration. However, the current methods need to depend on robustness of both tracking and segmentation procedures. RANSAC has been widely used to remove outliers in finding the vertical vanishing point and the horizon line, but the performance is degraded when the proportion of outliers is high. Last but not least, all of them require excessive simplifications in the algorithmic procedures resulting in increasing reprojection error. In this paper, a robust segmentation and tracking system is applied to provide accurate estimation of head and foot locations of moving persons. The noise in the computation of vanishing points is handled by mean shift clustering and Laplace linear regression through convex optimization. We also propose to use the estimation of distribution algorithm (EDA) to search for the local optimal solution for camera calibration that minimizes average reprojection error on the ground plane, while relaxing the assumptions on camera parameters. Promising evaluations of the performance of our proposed method on real scenes are presented.


## Honor
* Finalist IBM Best Track 3 Student Paper Award in ICPR 2016
<p align="center">
  <img src="http://zhengthomastang.github.io/images/SelfCalHum_award1.jpg?raw=true" alt="Award_IBM" style="width: 450px;"/> 
</p>
* Finalist Intel Best Track 3 Student Paper Award in ICPR 2016
<p align="center">
  <img src="http://zhengthomastang.github.io/images/SelfCalHum_award2.jpg?raw=true" alt="Award_Intel" style="width: 450px;"/> 
</p>


## Citation
@inproceedings{Tang16SelfCalHum,  
author = {Zheng Tang and Yen-Shuo Lin and Kuan-Hui Lee and Jenq-Neng Hwang and Jen-Hui Chuang and Zhijun Fang},  
title = {Camera self-calibration from tracking of moving persons},  
booktitle = {Proc. ICPR},  
pages = {260--265},  
address = {Canc\'{u}n, M\'{e}xico},  
year = {2016}  
}
