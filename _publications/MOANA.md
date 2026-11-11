---
title: 'MOANA: An Online Learned Adaptive Appearance Model for Robust Multiple Object Tracking in 3D'
collection: publications
permalink: /publications/MOANA
date: 2019-03-05
venue: IEEE Access
paperurl: https://ieeexplore.ieee.org/document/8660675
citation: '<b>Zheng Tang</b> and Jenq-Neng Hwang. "MOANA: An Online Learned Adaptive Appearance Model for Robust Multiple Object Tracking in 3D". <i>IEEE Access</i>. vol. 7, pp. 31934-31945. 2019.'
authors: Zheng Tang and Jenq-Neng Hwang
venue_short: IEEE Access
image: /images/MOANA_figure.jpg
excerpt: MOANA learns each target's appearance online to account for changes in viewpoint, pose, and lighting during multi-object tracking.
resources:
- label: Paper
  url: https://ieeexplore.ieee.org/document/8660675
- label: PETS09 demo
  url: https://motchallenge.net/vis/PETS09-S2L2/MOANA
- label: TownCentre demo
  url: https://motchallenge.net/vis/AVG-TownCentre/MOANA
---

{% include publication-links.html publication=page %}

## Summary

MOANA learns each target's appearance online to account for changes in viewpoint, pose, and lighting during multi-object tracking. Adaptive learning rates and spatial weighting support different feature representations, while cross-matching, re-identification, and 3D geometry help resolve occlusion and identity ambiguity. Evaluations on MOTChallenge report improved 3D tracking performance and real-time operation on a standard desktop CPU.

## Citation

```bibtex
@article{Tang19MOANA,
  author = {Zheng Tang and Jenq-Neng Hwang},
  title = { {MOANA}: {A}n online learned adaptive appearance model for robust multiple object tracking in {3D}},
  journal = {IEEE Access},
  volume = {7},
  pages = {31934--31945},
  year = {2019}
}
```
