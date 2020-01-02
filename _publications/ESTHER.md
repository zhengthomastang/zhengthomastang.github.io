---
title: "ESTHER: Joint Camera Self-Calibration and Automatic Radial Distortion Correction from Tracking of Walking Humans"
collection: publications
permalink: /publication/ESTHER
<!-- excerpt: 'This paper is about the number 1. The number 2 is left for future work.' -->
date: 2018-12-07
venue: "IEEE Access"
paperurl: "https://ieeexplore.ieee.org/document/8605504"
citation: '<b>Zheng Tang</b>, Yen-Shuo Lin, Kuan-Hui Lee, Jenq-Neng Hwang and Jen-Hui Chuang. "ESTHER: Joint Camera Self-Calibration and Automatic Radial Distortion Correction from Tracking of Walking Humans". <i>IEEE Access</i>. vol. 7, no. 1, pp. 10754-10766. 2019.'
---
## Abstract
Camera calibration and radial distortion correction are the crucial prerequisites for many applications in image big data and computer vision. Many existing works rely on the Manhattan world assumption to estimate the camera parameters automatically; however, they may perform poorly when there was lack of man-made structure in the scene. As walking humans are the common objects in video surveillance, they have also been used for camera self-calibration, but the main challenges include the noise reduction for the estimation of vanishing points, the relaxation of assumptions on unknown camera parameters, and the radial distortion correction. In this paper, we present a novel framework for camera self-calibration and automatic radial distortion correction. Our approach starts with the reliable human body segmentation that is facilitated by robust object tracking. Mean shift clustering and Laplace linear regression are, respectively, introduced in the estimation of the vertical vanishing point and the horizon line. The estimation of distribution algorithm, an evolutionary optimization scheme, is then utilized to optimize the camera parameters and the distortion coefficients, in which all the unknowns in camera projection can be fine-tuned simultaneously. Experiments on the three public benchmarks and our own captured dataset demonstrate the robustness of the proposed method. The superiority of this algorithm is also verified by the capability of reliably converting 2D object tracking into 3D space.


## Citation
@article{Tang19ESTHER,  
author = {Zheng Tang and Yen-Shuo Lin and Kuan-Hui Lee and Jenq-Neng Hwang},  
title = { {ESTHER}: {J}oint camera self-calibration and automatic radial distortion correction from tracking of walking humans},  
journal = {IEEE Access},  
volume = {7},  
number = {1},  
pages = {10754--10766},  
year = {2019}  
}