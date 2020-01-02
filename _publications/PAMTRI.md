---
title: "PAMTRI: Pose-Aware Multi-Task Learning for Vehicle Re-Identification Using Highly Randomized Synthetic Data"
collection: publications
permalink: /publication/PAMTRI
<!-- excerpt: 'This paper is about the number 1. The number 2 is left for future work.' -->
date: 2019-07-22
venue: "2019 IEEE/CVF International Conference on Computer Vision"
paperurl: "http://openaccess.thecvf.com/content_ICCV_2019/html/Tang_PAMTRI_Pose-Aware_Multi-Task_Learning_for_Vehicle_Re-Identification_Using_Highly_Randomized_ICCV_2019_paper.html"
citation: '<b>Zheng Tang</b>, Milind Naphade, Stan Birchfield, Jonathan Tremblay, William Hodge, Ratnesh Kumar, Shuo Wang and Xiaodong Yang. "PAMTRI: Pose-aware multi-task learning for vehicle re-identification using highly randomized synthetic data". <i>Proceedings of 2019 IEEE/CVF International Conference on Computer Vision (ICCV 2019)</i>. pp. 211-220. 2019.'
---
## Abstract
In comparison with person re-identification (ReID), which has been widely studied in the research community, vehicle ReID has received less attention. Vehicle ReID is challenging due to 1) high intra-class variability (caused by the dependency of shape and appearance on viewpoint), and 2) small inter-class variability (caused by the similarity in shape and appearance between vehicles produced by different manufacturers). To address these challenges, we propose a Pose-Aware Multi-Task Re-Identification (PAMTRI) framework. This approach includes two innovations compared with previous methods. First, it overcomes viewpoint-dependency by explicitly reasoning about vehicle pose and shape via keypoints, heatmaps and segments from pose estimation. Second, it jointly classifies semantic vehicle attributes (colors and types) while performing ReID, through multi-task learning with the embedded pose representations. Since manually labeling images with detailed pose and attribute information is prohibitive, we create a large-scale highly randomized synthetic dataset with automatically annotated vehicle attributes for training. Extensive experiments validate the effectiveness of each proposed component, showing that PAMTRI achieves significant improvement over state-of-the-art on two mainstream vehicle ReID benchmarks: VeRi and CityFlow-ReID.


## Citation
@inproceedings{Tang19PAMTRI,  
author = {Zheng Tang and Milind Naphade and Stan Birchfield and Jonathan Tremblay and William Hodge and Ratnesh Kumar and Shuo Wang and Xiaodong Yang},  
title = { {PAMTRI}: {P}ose-aware multi-task learning for vehicle re-identification using highly randomized synthetic data},  
booktitle = {Proc. ICCV},  
pages = {211--220},  
address = {Seoul, Korea},  
year = {2019}  
}