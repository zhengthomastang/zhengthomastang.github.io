---
title: "CityFlow: A City-Scale Benchmark for Multi-Target Multi-Camera Vehicle Tracking and Re-Identification"
collection: publications
permalink: /publication/CityFlow
<!-- excerpt: 'This paper is about the number 1. The number 2 is left for future work.' -->
date: 2019-02-24
venue: "2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition"
paperurl: "https://arxiv.org/abs/1903.09254"
citation: '<b>Zheng Tang</b>, Milind Naphade, Ming-Yu Liu, Xiaodong Yang, Stan Birchfield, Shuo Wang, Ratnesh Kumar, David Anastasiu and Jenq-Neng Hwang. "CityFlow: A City-Scale Benchmark for Multi-Target Multi-Camera Vehicle Tracking and Re-Identification". <i>Proceedings of 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2019)</i>. pp. 8797-8806. 2019.'
---
# CityFlow: A City-Scale Benchmark for Multi-Target Multi-Camera Vehicle Tracking and Re-Identification

[<a href="https://arxiv.org/abs/1903.09254">PDF</a>]
[<a href="https://youtu.be/fzJe8M2y1s0">Video</a>]
[<a href="http://zhengthomastang.github.io/files/CityFlow_slides.pdf">Slides</a>]
[<a href="http://zhengthomastang.github.io/files/CityFlow_poster.pdf">Poster</a>]
[<a href="https://www.aicitychallenge.org/2020-challenge/">Website</a>]

## Abstract
Urban traffic optimization using traffic cameras as sensors is driving the need to advance state-of-the-art multi-target multi-camera (MTMC) tracking. This work introduces CityFlow, a city-scale traffic camera dataset consisting of more than 3 hours of synchronized HD videos from 40 cameras across 10 intersections, with the longest distance between two simultaneous cameras being 2.5 km. To the best of our knowledge, CityFlow is the largest-scale dataset in terms of spatial coverage and the number of cameras/videos in an urban environment. The dataset contains more than 200K annotated bounding boxes covering a wide range of scenes, viewing angles, vehicle models, and urban traffic flow conditions. Camera geometry and calibration information are provided to aid spatio-temporal analysis. In addition, a subset of the benchmark is made available for the task of image-based vehicle re-identification (ReID). We conducted an extensive experimental evaluation of baselines/state-of-the-art approaches in MTMC tracking, multi-target single-camera (MTSC) tracking, object detection, and image-based ReID on this dataset, analyzing the impact of different network architectures, loss functions, spatio-temporal models and their combinations on task effectiveness. An evaluation server is launched with the release of our benchmark at the 2019 AI City Challenge (this https URL) that allows researchers to compare the performance of their newest techniques. We expect this dataset to catalyze research in this field, propel the state-of-the-art forward, and lead to deployed traffic optimization(s) in the real world.


## Citation
@inproceedings{Tang19CityFlow,  
author = {Zheng Tang and Milind Naphade and Ming-Yu Liu and Xiaodong Yang and Stan Birchfield and Shuo Wang and Ratnesh Kumar and David Anastasiu and Jenq-Neng Hwang},  
title = {City{F}low: {A} city-scale benchmark for multi-target multi-camera vehicle tracking and re-identification},  
booktitle = {Proc. CVPR},  
pages = {8797--8806},  
address = {Long Beach, CA, USA},  
year = {2019}  
}