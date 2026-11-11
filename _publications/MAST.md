---
title: Multiple-Kernel Adaptive Segmentation and Tracking (MAST) for Robust Object Tracking
collection: publications
permalink: /publications/MAST
date: 2016-03-20
venue: 2016 IEEE International Conference on Acoustics, Speech and Signal Processing
paperurl: https://ieeexplore.ieee.org/document/7471849
citation: <b>Zheng Tang</b>, Jenq-Neng Hwang, Yen-Shuo Lin and Jen-Hui Chuang. "Multiple-Kernel Adaptive Segmentation and Tracking (MAST) for Robust Object Tracking". <i>Proceedings of 2016 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP 2016)</i>. pp. 3064-3068. 2016.
authors: Zheng Tang, Jenq-Neng Hwang, Yen-Shuo Lin and Jen-Hui Chuang
venue_short: ICASSP 2016
image: /images/MAST_figure.jpg
excerpt: MAST improves object segmentation and tracking when foreground objects resemble the background or move through shadows.
resources:
- label: Paper
  url: https://ieeexplore.ieee.org/document/7471849
- label: Slides
  url: /files/MAST_slides.pdf
presentation: Oral
---

{% include publication-links.html publication=page %}

## Summary

MAST improves object segmentation and tracking when foreground objects resemble the background or move through shadows. An initial multiple-kernel tracker provides feedback that adapts background-subtraction and shadow-removal thresholds around each target. A second tracking pass uses the refined foreground masks. Evaluations on public benchmarks and recorded video examine the effect of this feedback loop on segmentation quality and tracking robustness.

## Citation

```bibtex
@inproceedings{Tang16MAST,
  author = {Zheng Tang and Jenq-Neng Hwang and Yen-Shuo Lin and Jen-Hui Chuang},
  title = {Multiple-kernel adaptive segmentation and tracking ({MAST}) for robust object tracking},
  booktitle = {Proc. ICASSP},
  pages = {1115--1119},
  address = {Shanghai, China},
  year = {2016}
}
```
