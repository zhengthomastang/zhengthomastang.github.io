---
title: "Single-Camera and Inter-Camera Vehicle Tracking and 3D Speed Estimation Based on Fusion of Visual and Semantic Features"
collection: publications
permalink: /publications/AICity18ICT
date: 2018-06-18
venue: "2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition - 2nd AI City Challenge Workshop"
paperurl: "http://openaccess.thecvf.com/content_cvpr_2018_workshops/w3/html/Tang_Single-Camera_and_Inter-Camera_CVPR_2018_paper.html"
citation: '<b>Zheng Tang</b>, Gaoang Wang, Hao Xiao, Aotian Zheng and Jenq-Neng Hwang. "Single-Camera and Inter-Camera Vehicle Tracking and 3D Speed Estimation Based on Fusion of Visual and Semantic Features". <i>Proceedings of 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW 2018)</i>. pp. 108-115. 2018.'
---

# Single-Camera and Inter-Camera Vehicle Tracking and 3D Speed Estimation Based on Fusion of Visual and Semantic Features

[<a href="http://openaccess.thecvf.com/content_cvpr_2018_workshops/w3/html/Tang_Single-Camera_and_Inter-Camera_CVPR_2018_paper.html">Paper</a>]
[<a href="https://github.com/zhengthomastang/2018AICity_TeamUW">Code</a>]
[<a href="http://zhengthomastang.github.io/files/AICity18ICT_slides.pdf">Slides</a>]
[<a href="http://zhengthomastang.github.io/files/AICity18ICT_poster.pdf">Poster</a>]
[<a href="https://youtu.be/_i4numqiv7Y">Demo1</a>]
[<a href="https://youtu.be/Jlvh_KxHl40">Demo2</a>]

## Abstract
Tracking of vehicles across multiple cameras with non-overlapping views has been a challenging task for the intelligent transportation system (ITS). It is mainly because of high similarity among vehicle models, frequent occlusion, large variation in different viewing perspectives and low video resolution. In this work, we propose a fusion of visual and semantic features for both single-camera tracking (SCT) and inter-camera tracking (ICT). Specifically, a histogram-based adaptive appearance model is introduced to learn long-term history of visual features for each vehicle target. Besides, semantic features including trajectory smoothness, velocity change and temporal information are incorporated into a bottom-up clustering strategy for data association in each single camera view. Across different camera views, we also exploit other information, such as deep learning features, detected license plate features and detected car types, for vehicle re-identification. Additionally, evolutionary optimization is applied to camera calibration for reliable 3D speed estimation. Our algorithm achieves the top performance in both 3D speed estimation and vehicle re-identification at the NVIDIA AI City Challenge 2018.

## Honor
* Winner of Track 1 (Traffic Flow Analysis) at the 2nd AI City Challenge Workshop in CVPR 2018
* Winner of Track 3 (Multi-camera Vehicle Detection & ReID) at the 2nd AI City Challenge Workshop in CVPR 2018
<p align="center">
  <img src="http://zhengthomastang.github.io/images/AICity18ICT_photo.jpg?raw=true" alt="Photo" style="width: 450px;"/> 
</p>

## Citation
@inproceedings{Tang18AICity18ICT,  
author = {Zheng Tang and Gaoang Wang and Hao Xiao and Aotian Zheng and Jenq-Neng Hwang},  
title = {Single-camera and inter-camera vehicle tracking and {3D} speed estimation based on fusion of visual and semantic features},  
booktitle = {Proc. CVPR Workshops},  
pages = {108--115},  
address = {Salt Lake City, UT, USA},  
year = {2018}  
}
