---
title: "Fourier PlenOctrees for Dynamic Radiance Field Rendering in Real-time"
collection: publications
permalink: /publication/2022-fourier-plenoctree
excerpt:  'In this paper, we present a novel Fourier PlenOctree (FPO) technique to tackle efficient neural modeling and real-time rendering of dynamic scenes captured under the free-view video (FVV) setting.'
date: 2022-1-1
venue: 'Accepted at CVPR 2022'
paperurl: 'https://arxiv.org/pdf/2202.08614.pdf'
codeurl: 'https://aoliao12138.github.io/FPO/'
projecturl: 'https://aoliao12138.github.io/FPO/'
authors: 'Liao Wang*, Jiakai Zhang*, Xinhang Liu, Fuqiang Zhao, Yanshun Zhang, Yingliang Zhang, Minye Wu, Lan Xu, Jingyi Yu'
---
Implicit neural representations such as Neural Radiance Field (NeRF) have largely focused on modeling static objects captured under multi-view settings where real-time rendering can be achieved with smart data structures, e.g., PlenOctree. In this paper, we present a novel Fourier PlenOctree (FPO) technique to tackle efficient neural modeling and real-time rendering of dynamic scenes captured under the free-view video (FVV) setting. The key idea in our FPO is an ingenious combination of generalized NeRF, PlenOctree representation, volumetric fusion and Fourier transform. For accelerate FPO construction, we present a novel coarse-to-fine fusion scheme that leverages generalizable NeRF technique to generate the tree via spatial blending. To tackle dynamic scenes, we tailor the implicit network to model the Fourier coefficients of time-varying density and color attributes. Finally we construct the FPO and train the Fourier coefficients directly on the leaves of a union PlenOctree structure of the dynamic sequence. We show the resulting FPO enables compact memory overload to handle dynamic objects and supports efficient fine-tuning. Extensive experiments show that the proposed method is 3000 times faster than original NeRF and achieves over an order of magnitude acceleration over SOTA while preserving high visual quality for free-viewpoint rendering of unseen dynamic scenes.
[Project Page](https://aoliao12138.github.io/FPO/) |  [Paper](https://arxiv.org/pdf/2202.08614.pdf) 
