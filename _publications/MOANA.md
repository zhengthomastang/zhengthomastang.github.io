---
title: "MOANA: An Online Learned Adaptive Appearance Model for Robust Multiple Object Tracking in 3D"
collection: publications
permalink: /publication/MOANA
<!-- excerpt: 'This paper is about the number 1. The number 2 is left for future work.' -->
date: 2019-03-05
venue: "IEEE Access"
paperurl: "https://ieeexplore.ieee.org/document/8660675"
citation: '<b>Zheng Tang</b> and Jenq-Neng Hwang. "MOANA: An Online Learned Adaptive Appearance Model for Robust Multiple Object Tracking in 3D". <i>IEEE Access</i>. vol. 7, no. 1, pp. 31934-31945. 2019.'
---
# MOANA: An Online Learned Adaptive Appearance Model for Robust Multiple Object Tracking in 3D

[<a href="https://ieeexplore.ieee.org/document/8660675">Paper</a>]
[<a href="https://motchallenge.net/vis/PETS09-S2L2/MOANA">Demo1</a>]
[<a href="https://motchallenge.net/vis/AVG-TownCentre/MOANA">Demo2</a>]


## Abstract
Multiple object tracking has been a challenging field, mainly due to noisy detection sets an identity switch caused by occlusion and similar appearance among nearby targets. Previous works rely on appearance models that are built on an individual or several selected frames for the comparison of features, but they cannot encode the long-term appearance changes caused by pose, viewing angle, and lighting conditions. In this paper, we propose an adaptive model that learns online a relatively long-term appearance change of each target. The proposed model is compatible with any feature of fixed dimension or their combination, whose learning rates are dynamically controlled by the adaptive update and spatial weighting schemes. To handle occlusion and nearby objects that are sharing a similar appearance, we also design the cross-matching and re-identification schemes based on the application of the proposed adaptive appearance models. In addition, the 3D geometry information is effectively incorporated in our formulation for data association. The proposed method outperforms all the state of the art on the MOTChallenge 3D benchmark and achieves real-time computation with only a standard desktop CPU. It has also shown superior performance over the state of the art on the 2D benchmark of MOTChallenge.


## Citation
@article{Tang19MOANA,  
author = {Zheng Tang and Jenq-Neng Hwang},  
title = { {MOANA}: {A}n online learned adaptive appearance model for robust multiple object tracking in {3D}},  
journal = {IEEE Access},  
volume = {7},  
number = {1},  
pages = {31934--31945},  
year = {2019}  
}
