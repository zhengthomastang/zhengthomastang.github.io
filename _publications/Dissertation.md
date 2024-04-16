---
title: "Robust Video Object Tracking via Camera Self-Calibration"
collection: publications
permalink: /publication/Dissertation
<!-- excerpt: 'This paper is about the number 1. The number 2 is left for future work.' -->
date: 2019-06-14
venue: "Ph.D. dissertation. Department of Electrical & Computer Engineering, University of Washington, Seattle, WA"
paperurl: "http://hdl.handle.net/1773/43951"
citation: '<b>Zheng Tang</b>. "Robust Video Object Tracking via Camera Self-Calibration". Ph.D. dissertation. University of Washington, Seattle, WA. 2019.'
---
# Robust Video Object Tracking via Camera Self-Calibration

[<a href="http://hdl.handle.net/1773/43951">Paper</a>]
[<a href="http://zhengthomastang.github.io/files/Dissertation_slides.pdf">Slides</a>]


## Abstract
In this dissertation, a framework for 3D scene reconstruction based on robust video object tracking assisted by camera self-calibration is proposed, which includes several algorithmic components. (1) An algorithm for joint camera self-calibration and automatic radial distortion correction based on tracking of walking persons is designed to convert multiple object tracking into 3D space. (2) An adaptive model that learns online a relatively long-term appearance change of each target is proposed for robust 3D tracking. (3) We also develop an iterative two-step evolutionary optimization scheme to estimate 3D pose of each human target, which can jointly compute the camera trajectory for a moving camera as well. (4) With 3D tracking results and human pose information from multiple views, we propose multi-view 3D scene reconstruction based on data association with visual and semantic attributes. 

Camera calibration and radial distortion correction are crucial prerequisites for 3D scene understanding. Many existing works rely on the Manhattan world assumption to estimate camera parameters automatically, however, they may perform poorly when lack of man-made structure in the scene. As walking humans are common objects in video analytics, they have also been used for camera calibration, but the main challenges include noise reduction for the estimation of vanishing points, the relaxation of assumptions on unknown camera parameters, and radial distortion correction. We propose a novel framework for camera self-calibration and automatic radial distortion correction. Our approach starts with a multi-kernel-based adaptive segmentation and tracking scheme that dynamically controls the decision thresholds of background subtraction and shadow removal around the adaptive kernel regions based on the preliminary tracking results. With the head/foot points collected from tracking and segmentation results, mean shift clustering and Laplace linear regression are introduced in the estimation of the vertical vanishing point and the horizon line, respectively. The estimation of distribution algorithm (EDA), an evolutionary optimization scheme, is then utilized to optimize the camera parameters and distortion coefficients, in which all the unknowns in camera projection can be fine-tuned simultaneously. Experiments on three public benchmarks and our own captured dataset demonstrate the robustness of the proposed method. The superiority of this algorithm is also verified by the capability of reliably converting 2D object tracking into 3D space. 

Multiple object tracking has been a challenging field, mainly due to noisy detection sets and identity switch caused by occlusion and similar appearance among nearby targets. Previous works rely on appearance models built on individual or several selected frames for the comparison of features, but they cannot encode long-term appearance change caused by pose, viewing angle and lighting condition. We propose an adaptive model that learns online a relatively long-term appearance change of each target. The proposed model is compatible with any features of fixed dimension or their combinations, whose learning rates are dynamically controlled by adaptive update and spatial weighting schemes. To handle occlusion and nearby objects sharing similar appearance, we also design cross-matching and re-identification schemes based on the proposed adaptive appearance models. Additionally, the 3D geometry information is effectively incorporated in our formulation for data association. The proposed method outperforms all the state-of-the-art on the MOTChallenge 3D benchmark and achieves real-time computation with only a standard desktop CPU. It has also shown superior performance over the state-of-the-art on the 2D benchmark of MOTChallenge. 

For more comprehensive 3D scene reconstruction, we develop a monocular 3D human pose estimation algorithm based on two-step EDA that can simultaneously estimate the camera motion for a moving camera. We first derive reliable 2D joint points through deep-learning-based 2D pose estimation and feature tracking. If the camera is moving, the initial camera poses can be estimated from visual odometry, where the feature points extracted on the human bodies are removed by segmentation masks dilated from 2D skeletons. Then the 3D joint points and camera parameters are iteratively optimized through a two-step evolutionary algorithm. The cost function for human pose optimization consists of loss terms defined by spatial and temporal constancy, "flatness" of human bodies, and joint angle constraints. On the other hand, the optimization for camera movement is based on the minimization of reprojection error of skeleton joint points. Extensive experiments have been conducted on various video data, which verify the robustness of the proposed method. 

The final goal of our work is to fully understand and reconstruct the 3D scene, i.e., to recover the trajectory and action of each object. The above methods can be extended to a system with camera array of overlapping views. We propose a novel video scene reconstruction framework to collaboratively track multiple human objects and estimate their 3D poses across multiple camera views. First, tracklets are extracted from each single view following the tracking-by-detection paradigm. We propose an effective integration of visual and semantic object attributes, including appearance models, geometry information and poses/actions, to associate tracklets across different views. Based on the optimum viewing perspectives derived from tracking, we generate the 3D skeleton of each object. The estimated body joint points are fed back to the tracking stage to enhance tracklet association. Experiments on a benchmark of multi-view tracking validate our effectiveness.


## Citation
@phdthesis{Tang19Dissertation,  
author = {Zheng Tang},  
title = {Robust video object tracking via camera self-calibration},  
school = {University of Washington, Seattle, WA},  
year = {2019}  
}
