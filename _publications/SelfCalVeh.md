---
title: "Self-Calibration of Traffic Surveillance Cameras Based on Moving Vehicle Appearance and 3-D Vehicle Modeling"
collection: publications
permalink: /publication/SelfCalVeh
date: 2018-10-07
venue: "2018 IEEE International Conference on Image Processing"
paperurl: "https://ieeexplore.ieee.org/document/8451478"
citation: 'Na Wang, Haiqing Du, Yong Liu, <b>Zheng Tang</b> and Jenq-Neng Hwang. "Self-Calibration of Traffic Surveillance Cameras Based on Moving Vehicle Appearance and 3-D Vehicle Modeling". <i>Proceedings of 2018 IEEE International Conference on Image Processing (ICIP 2018)</i>. pp. 3064-3068. 2018.'
---
# Self-Calibration of Traffic Surveillance Cameras Based on Moving Vehicle Appearance and 3-D Vehicle Modeling

[<a href="https://ieeexplore.ieee.org/document/8451478">Paper</a>]

## Abstract
This paper proposes an effective and practical method for self-calibration of traffic surveillance cameras. Based on analyzing multiple moving vehicles across multiple frames, the Canny edge detector and Hough transform are first adopted to obtain orthogonal horizontal vanishing points pairs, from which corresponding vertical vanishing points are derived. Next, mean shift clustering and Laplace linear regression are employed to deal with noise and outliers during estimation of vanishing points. To overcome the unreliable estimation issues of orthogonal vanishing points pairs, we further utilize the projective line segments obtained from 3-D vehicle model to create more reliable pairs and iteratively improve the calibration results. Finally, the estimation of distribution algorithm (EDA) is also applied to relax the assumptions made on camera parameters and the moving trajectories of vehicles during the iterations. Experimental results on different datasets prove the feasibility of our proposed scheme.


## Citation
@inproceedings{Wang18SelfCalVeh,  
author = {Na Wang and Haiqing Du and Yong Liu and Zheng Tang and Jenq-Neng Hwang},  
title = {Self-calibration of traffic surveillance cameras based on moving vehicle appearance and 3-D vehicle modeling},  
booktitle = {Proc. ICIP},  
pages = {3064--3068},   
address = {Athens, Greece},  
year = {2018}  
}
