---
title: 'ESTHER: Joint Camera Self-Calibration and Automatic Radial Distortion Correction from Tracking of Walking Humans'
collection: publications
permalink: /publications/ESTHER
date: 2019-01-08
venue: IEEE Access
paperurl: https://ieeexplore.ieee.org/document/8605504
citation: '<b>Zheng Tang</b>, Yen-Shuo Lin, Kuan-Hui Lee, Jenq-Neng Hwang and Jen-Hui Chuang. "ESTHER: Joint Camera Self-Calibration and Automatic Radial Distortion Correction from Tracking of Walking Humans". <i>IEEE Access</i>. vol. 7, pp. 10754-10766. 2019.'
authors: Zheng Tang, Yen-Shuo Lin, Kuan-Hui Lee, Jenq-Neng Hwang and Jen-Hui Chuang
venue_short: IEEE Access
image: /images/ESTHER_figure.jpg
excerpt: ESTHER jointly estimates camera parameters and radial distortion from tracked walking people.
resources:
- label: Paper
  url: https://ieeexplore.ieee.org/document/8605504
---

{% include publication-links.html publication=page %}

## Summary

ESTHER jointly estimates camera parameters and radial distortion from tracked walking people. Tracking-assisted segmentation supplies head and foot observations; mean-shift clustering and Laplace regression estimate vanishing points. An evolutionary optimization method then refines camera and distortion parameters together. Evaluations on public benchmarks and captured video examine calibration robustness and the resulting conversion of 2D object tracks into 3D scene coordinates.

## Citation

```bibtex
@article{Tang19ESTHER,
  author = {Zheng Tang and Yen-Shuo Lin and Kuan-Hui Lee and Jenq-Neng Hwang},
  title = { {ESTHER}: {J}oint camera self-calibration and automatic radial distortion correction from tracking of walking humans},
  journal = {IEEE Access},
  volume = {7},
  pages = {10754--10766},
  year = {2019}
}
```
