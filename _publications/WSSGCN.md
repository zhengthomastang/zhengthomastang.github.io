---
title: "WSSGCN: Wide Sub-stage Graph Convolutional Networks"
collection: publications
permalink: /publications/WSSGCN
date: 2024-07-29
venue: "Neurocomputing"
paperurl: "https://www.sciencedirect.com/science/article/pii/S0925231224010440"
citation: 'Chao Wang, <b>Zheng Tang</b> and Hailu Xu. "WSSGCN: Wide Sub-stage Graph Convolutional Networks". <i>Neurocomputing</i>. vol. 602, p. 128273. 2024.'
---

## Abstract
Graph Convolutional Networks (GCNs) have emerged as a potent tool for learning graph representations, finding applications in a plethora of real-world scenarios. Nevertheless, a significant portion of deep learning research has predominantly concentrated on enhancing model performance via the construction of deeper GCNs. Regrettably, the efficacy of training deep GCNs is marred by two fundamental weaknesses: the inadequacy of conventional methodologies in handling heterogeneous networks, and the exponential surge in model complexity as network depth increases. This, in turn, imposes constraints on their practical utility. To surmount these inherent limitations, we propose an innovative approach named the Wide Sub-stage Graph Convolutional Network (WSSGCN). Our method is an outcome of meticulous observations drawn from classical and graph convolutional networks, aimed at rectifying the constraints associated with traditional GCNs. Our strategy involves the conception of a staged convolutional network framework that mirrors the fundamental tenets of the step-by-step learning process akin to human cognition. This framework prioritizes three distinct forms of consistency: response-based, feature-based, and relationship-based. Our approach involves three tailored convolutional networks capturing node/edge, subgraph, and global features. Additionally, we introduce a novel method to expand graph width for efficient GCN training. Empirical validation on benchmarks highlights WSSGCN's superior accuracy and faster training versus conventional GCNs. WSSGCN triumphs over traditional GCN constraints, significantly enhancing graph representation learning.

## BibTeX
@article{Wang24WSSGCN,  
author={Chao Wang and Zheng Tang and Hailu Xu},  
title = { {WSSGCN}: {W}ide sub-stage graph convolutional networks},  
journal = {Neurocomputing},  
volume = {602},  
pages = {128273},  
year = {2024}  
}
