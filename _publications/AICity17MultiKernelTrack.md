---
title: Multiple-Kernel Based Vehicle Tracking Using 3D Deformable Model and Camera Self-Calibration
collection: publications
permalink: /publications/AICity17MultiKernelTrack
date: 2017-08-05
venue: 2017 IEEE Smart World Congress - 1st AI City Challenge Workshop
paperurl: https://arxiv.org/abs/1708.06831
citation: <b>Zheng Tang</b>, Gaoang Wang, Tao Liu, Young-Gun Lee, Adwin Jahn, Xu Liu, Xiaodong He and Jenq-Neng Hwang. "Multiple-Kernel Based Vehicle Tracking Using 3D Deformable Model and Camera Self-Calibration". <i>arXiv:1708.06831</i>. 2017.
authors: Zheng Tang, Gaoang Wang, Tao Liu, Young-Gun Lee, Adwin Jahn, Xu Liu, Xiaodong He and Jenq-Neng Hwang
venue_short: SmartWorld Workshop 2017
image: /images/AICity17MultiKernelTrack_figure.jpg
excerpt: This vehicle-tracking system combines 3D deformable vehicle models, constrained multiple-kernel tracking, and camera self-calibration.
resources:
- label: Paper
  url: https://arxiv.org/abs/1708.06831
- label: Slides
  url: /files/AICity17MultiKernelTrack_slides.pdf
- label: Demo
  url: https://youtu.be/QA0Iek4tR0k
---

{% include publication-links.html publication=page %}

## Summary

This vehicle-tracking system combines 3D deformable vehicle models, constrained multiple-kernel tracking, and camera self-calibration. It uses shape and appearance cues to maintain tracks through occlusion, while tracking feedback refines foreground segmentation. Camera parameters are estimated from walking people, and an ensemble of SSD and YOLO9000 detections supports vehicle localization. The system won the AI City Applications track at the first AI City Challenge.

## Recognition

- Winner of Track 2 (AI City Applications) at the 1st AI City Challenge Workshop in SmartWorld 2017

![Award](/images/AICity17MultiKernelTrack_award.png)

![Photo](/images/AICity17MultiKernelTrack_photo.png)

## Citation

```bibtex
@misc{Tang17AICity17MultiKernelTrack,
  author = {Zheng Tang and Gaoang Wang and Tao Liu and Young-Gun Lee and Adwin Jahn and Xu Liu and Xiaodong He and Jenq-Neng Hwang},
  title = {Multiple-kernel based vehicle tracking using {3D} deformable model and camera self-calibration},
  howpublished = {arXiv:1708.06831},
  year = {2017}
}
```
