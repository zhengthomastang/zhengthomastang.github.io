---
title: "Training with Product Digital Twins for AutoRetail Checkout"
collection: publications
permalink: /publications/ARC
date: 2023-08-18
venue: "arXiv"
paperurl: "https://arxiv.org/abs/2308.09708"
citation: 'Yue Yao, Xinyu Tian, <b>Zheng Tang</b>, Sujit Biswas, Huan Lei, Tom Gedeon and Liang Zheng. "Training with Product Digital Twins for AutoRetail Checkout". <i>arXiv:2308.09708</i>. 2023.'
---

[<a href="https://arxiv.org/abs/2308.09708">Paper</a>]

## Abstract
Automating the checkout process is important in smart retail, where users effortlessly pass products by hand through a camera, triggering automatic product detection, tracking, and counting. In this emerging area, due to the lack of annotated training data, we introduce a dataset comprised of product 3D models, which allows for fast, flexible, and large-scale training data generation through graphic engine rendering. Within this context, we discern an intriguing facet, because of the user "hands-on" approach, bias in user behavior leads to distinct patterns in the real checkout process. The existence of such patterns would compromise training effectiveness if training data fail to reflect the same. To address this user bias problem, we propose a training data optimization framework, i.e., training with digital twins (DtTrain). Specifically, we leverage the product 3D models and optimize their rendering viewpoint and illumination to generate "digital twins" that visually resemble representative user images. These digital twins, inherit product labels and, when augmented, form the Digital Twin training set (DT set). Because the digital twins individually mimic user bias, the resulting DT training set better reflects the characteristics of the target scenario and allows us to train more effective product detection and tracking models. In our experiment, we show that DT set outperforms training sets created by existing dataset synthesis methods in terms of counting accuracy. Moreover, by combining DT set with pseudo-labeled real checkout data, further improvement is observed. The code is available at https://github.com/yorkeyao/Automated-Retail-Checkout.

## Citation
@misc{Yao24ARC,  
author = {Yue Yao and Xinyu Tian and Zheng Tang and Sujit Biswas and Huan Lei and Tom Gedeon and Liang Zheng},  
title = {Training with product digital twins for {A}uto{R}etail {C}heckout},  
note = {arXiv:2308.09708 (submitted to TNNLS)},  
year = {2024}  
}
