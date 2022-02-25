---
title: "HumanNeRF: Generalizable Neural Human Radiance Field from Sparse Inputs"
collection: publications
permalink: /publication/2022-humannerf
excerpt: 'We present HumanNeRF - a generalizable neural representation - for high-fidelity free-view synthesis of dynamic humans.'
date: 2022-1-1
venue: 'Arxiv'
paperurl: 'https://arxiv.org/pdf/2112.02789.pdf'
codeurl: 'https://zhaofuq.github.io/human-nerf/'
projecturl: 'https://zhaofuq.github.io/human-nerf/'
twominutepaperurl: 'https://www.youtube.com/watch?v=u_11uchP08Y'
authors: 'Fuqiang Zhao, Wei Yang, Jiakai Zhang, Pei Lin, Yingliang Zhang, Jingyi Yu, Lan Xu'
---
Recent neural human representations can produce high-quality multi-view rendering but require using dense multi-view inputs and costly training. They are hence largely limited to static models as training each frame is infeasible. We present HumanNeRF - a generalizable neural representation - for high-fidelity free-view synthesis of dynamic humans. Analogous to how IBRNet assists NeRF by avoiding per-scene training, HumanNeRF employs an aggregated pixel-alignment feature across multi-view inputs along with a pose embedded non-rigid deformation field for tackling dynamic motions. The raw HumanNeRF can already produce reasonable rendering on sparse video inputs of unseen subjects and camera settings. To further improve the rendering quality, we augment our solution with an appearance blending module for combining the benefits of both neural volumetric rendering and neural texture blending. Extensive experiments on various multi-view dynamic human datasets demonstrate the generalizability and effectiveness of our approach in synthesizing photo-realistic free-view humans under challenging motions and with very sparse camera view inputs.

[Project Page](https://zhaofuq.github.io/human-nerf/) |  [Paper](https://arxiv.org/pdf/2112.02789.pdf) 
