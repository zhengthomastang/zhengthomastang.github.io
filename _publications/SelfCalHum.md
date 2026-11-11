---
title: Camera Self-Calibration from Tracking of Moving Persons
collection: publications
permalink: /publications/SelfCalHum
date: 2016-12-04
venue: 2016 International Conference on Pattern Recognition
paperurl: https://ieeexplore.ieee.org/document/7899644
citation: <b>Zheng Tang</b>, Yen-Shuo Lin, Kuan-Hui Lee, Jenq-Neng Hwang, Jen-Hui Chuang and Zhijun Fang. "Camera Self-Calibration from Tracking of Moving Persons". <i>Proceedings of 2016 International Conference on Pattern Recognition (ICPR 2016)</i>. pp. 260-265. 2016.
authors: Zheng Tang, Yen-Shuo Lin, Kuan-Hui Lee, Jenq-Neng Hwang, Jen-Hui Chuang and Zhijun Fang
venue_short: ICPR 2016
image: /images/SelfCalHum_figure.png
excerpt: This method estimates static-camera parameters from the tracked head and foot positions of walking people.
resources:
- label: Paper
  url: https://ieeexplore.ieee.org/document/7899644
- label: Slides
  url: /files/SelfCalHum_slides.pdf
- label: Demo
  url: https://youtu.be/Lqe8AgCxiRg
---

{% include publication-links.html publication=page %}

## Summary

This method estimates static-camera parameters from the tracked head and foot positions of walking people. Mean-shift clustering and Laplace regression reduce noise in vanishing-point estimation, while an estimation-of-distribution algorithm refines camera parameters by minimizing reprojection error. Evaluations on real scenes examine calibration robustness and the conversion of image observations into 3D ground-plane measurements.

## Recognition

- Finalist IBM Best Track 3 Student Paper Award in ICPR 2016

![Award IBM](/images/SelfCalHum_award1.jpg)

- Finalist Intel Best Track 3 Student Paper Award in ICPR 2016

![Award Intel](/images/SelfCalHum_award2.jpg)

## Citation

```bibtex
@inproceedings{Tang16SelfCalHum,
  author = {Zheng Tang and Yen-Shuo Lin and Kuan-Hui Lee and Jenq-Neng Hwang and Jen-Hui Chuang and Zhijun Fang},
  title = {Camera self-calibration from tracking of moving persons},
  booktitle = {Proc. ICPR},
  pages = {260--265},
  address = {Canc\'{u}n, M\'{e}xico},
  year = {2016}
}
```
