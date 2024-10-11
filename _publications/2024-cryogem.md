---
title: "CryoGEM: Physics-Informed Generative Cryo-Electron Microscopy"

collection: publications
permalink: /publication/cryogem
excerpt: 'we introduce physics-informed generative cryo-electron microscopy (CryoGEM), which for the first time integrates physics-based cryo-EM simulation with a generative unpaired noise translation to generate physically correct synthetic cryo-EM datasets with realistic noises.'
date: 2024-12-09
projecturl: 'https://jiakai-zhang.github.io/cryogem/'
venue: 'NeurIPS 2024'
paperurl: 'https://arxiv.org/pdf/2312.02235'
codeurl: 'https://github.com/Cellverse/CryoGEM/tree/main'
authors: 'Jiakai Zhang*, Qihe Chen*, Yan Zeng,  Wenyuan Gao,  Xuming He,  Zhijie Liu,  and Jingyi Yu'
---
In the past decade, deep conditional generative models have revolutionized the generation of realistic images, extending their application from entertainment to scientific domains. Single-particle cryo-electron microscopy (cryo-EM) is crucial in resolving near-atomic resolution 3D structures of proteins, such as the SARS-COV-2 spike protein. To achieve high-resolution reconstruction, a comprehensive data processing pipeline has been adopted. However, its performance is still limited as it lacks high-quality annotated datasets for training. To address this, we introduce physics-informed generative cryo-electron microscopy (CryoGEM), which for the first time integrates physics-based cryo-EM simulation with a generative unpaired noise translation to generate physically correct synthetic cryo-EM datasets with realistic noises. Initially, CryoGEM simulates the cryo-EM imaging process based on a virtual specimen. To generate realistic noises, we leverage an unpaired noise translation via contrastive learning with a novel mask-guided sampling scheme. Extensive experiments show that CryoGEM is capable of generating authentic cryo-EM images. The generated dataset can used as training data for particle picking and pose estimation models, eventually improving the reconstruction resolution.
