---
title: 'PAMTRI: Pose-Aware Multi-Task Learning for Vehicle Re-Identification Using Highly Randomized Synthetic Data'
collection: publications
permalink: /publications/PAMTRI
date: 2019-10-27
venue: 2019 International Conference on Computer Vision
paperurl: https://arxiv.org/abs/2005.00673
citation: '<b>Zheng Tang</b>, Milind Naphade, Stan Birchfield, Jonathan Tremblay, William Hodge, Ratnesh Kumar, Shuo Wang and Xiaodong Yang. "PAMTRI: Pose-Aware Multi-Task Learning for Vehicle Re-Identification Using Highly Randomized Synthetic Data". <i>Proceedings of 2019 International Conference on Computer Vision (ICCV 2019)</i>. pp. 211-220. 2019.'
authors: Zheng Tang, Milind Naphade, Stan Birchfield, Jonathan Tremblay, William Hodge, Ratnesh Kumar, Shuo Wang and Xiaodong Yang
venue_short: ICCV 2019
image: /images/PAMTRI_figure.png
excerpt: PAMTRI combines vehicle re-identification with pose estimation and attribute learning.
resources:
- label: Paper
  url: https://arxiv.org/abs/2005.00673
- label: Code
  url: https://github.com/NVlabs/PAMTRI
- label: Poster
  url: /files/PAMTRI_poster.png
---

{% include publication-links.html publication=page %}

## Summary

PAMTRI combines vehicle re-identification with pose estimation and attribute learning. Pose keypoints, heatmaps, and segments help address viewpoint variation, while joint color and type prediction provide additional supervision. Highly randomized synthetic vehicles supply pose and attribute labels without manual annotation. Experiments on VeRi and CityFlow-ReID evaluate the contribution of each component to cross-camera vehicle matching.

## Citation

```bibtex
@inproceedings{Tang19PAMTRI,
  author = {Zheng Tang and Milind Naphade and Stan Birchfield and Jonathan Tremblay and William Hodge and Ratnesh Kumar and Shuo Wang and Xiaodong Yang},
  title = { {PAMTRI}: {P}ose-aware multi-task learning for vehicle re-identification using highly randomized synthetic data},
  booktitle = {Proc. ICCV},
  pages = {211--220},
  address = {Seoul, Korea},
  year = {2019}
}
```
