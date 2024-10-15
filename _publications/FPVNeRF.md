---
title: "Radiance Field Learners As UAV First-Person Viewers"
collection: publications
permalink: /publication/FPVNeRF
date: 2024-09-29
venue: "2024 European Conference on Computer Vision"
paperurl: "https://arxiv.org/abs/2408.05533"
citation: 'Liqi Yan, Qifan Wang, Junhan Zhao, Qiang Guan, <b>Zheng Tang</b>, Jianhui Zhang and Dongfang Liu. "Radiance Field Learners As UAV First-Person Viewers". <i>Proceedings of 2024 European Conference on Computer Vision (ECCV 2024)</i>. 2024.'
---

[<a href="https://arxiv.org/abs/2408.05533">Paper</a>]
[<a href="https://fpv-nerf.github.io/">Website</a>]
[<a href="https://1drv.ms/f/s!AqSHE4twhUJ5nlDk2MzOk2kLGKiH">Dataset</a>]

## Abstract
First-Person-View (FPV) holds immense potential for revolutionizing the trajectory of Unmanned Aerial Vehicles (UAVs), offering an exhilarating avenue for navigating complex building structures. Yet, traditional Neural Radiance Field (NeRF) methods face challenges such as sampling single points per iteration and requiring an extensive array of views for supervision. UAV videos exacerbate these issues with limited viewpoints and significant spatial scale variations, resulting in inadequate detail rendering across diverse scales. In response, we introduce FPV-NeRF, addressing these challenges through three key facets: (1) Temporal consistency. Leveraging spatio-temporal continuity ensures seamless coherence between frames; (2) Global structure. Incorporating various global features during point sampling preserves space integrity; (3) Local granularity. Employing a comprehensive framework and multi-resolution supervision for multi-scale scene feature representation tackles the intricacies of UAV video spatial scales. Additionally, due to the scarcity of publicly available FPV videos, we introduce an innovative view synthesis method using NeRF to generate FPV perspectives from UAV footage, enhancing spatial perception for drones. Our novel dataset spans diverse trajectories, from outdoor to indoor environments, in the UAV domain, differing significantly from traditional NeRF scenarios. Through extensive experiments encompassing both interior and exterior building structures, FPV-NeRF demonstrates a superior understanding of the UAV flying space, outperforming state-of-the-art methods in our curated UAV dataset. Explore our project page for further insights: [https://fpv-nerf.github.io/](https://fpv-nerf.github.io/).

## BibTeX
@inproceedings{Yan24FPVNeRF,  
author = {Liqi Yan and Qifan Wang and Junhan Zhao and Qiang Guan and Zheng Tang and Jianhui Zhang and Dongfang Liu},  
title = {Radiance field learners as {UAV} first-person viewers},  
booktitle = {Proc. ECCV},  
address = {Milan, Italy},  
year = {2024}  
}
