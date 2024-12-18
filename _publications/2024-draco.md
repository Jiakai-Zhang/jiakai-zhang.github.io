---
title: "DRACO: A Denoising-Reconstruction Autoencoder for Cryo-EM"

collection: publications
permalink: /publication/draco
excerpt: 'We introduce DRACO, a Denoising-Reconstruction Autoencoder for CryO-EM, inspired by the Noise2Noise (N2N) approach.'
projecturl: 'https://duskngai.github.io/draco/'
date: 2024-12-09
venue: 'NeurIPS 2024'
paperurl: 'https://duskngai.github.io/draco/static/DRACO.pdf'
authors: 'Yingjun Shen*,  Haizhao Dai*,  Qihe Chen,  Yan Zeng,  Jiakai Zhang,  Yuan Pei, Jingyi Yu'
---
Foundation models in computer vision have demonstrated exceptional performance in zero-shot and few-shot tasks by extracting multi-purpose features from large-scale datasets through self-supervised pre-training methods. However, these models often overlook the severe corruption in cryogenic electron microscopy (cryo-EM) images by high-level noises. We introduce DRACO, a Denoising-Reconstruction Autoencoder for CryO-EM, inspired by the Noise2Noise (N2N) approach. By processing cryo-EM movies into odd and even images and treating them as independent noisy observations, we apply a denoising-reconstruction hybrid training scheme. We mask both images to create denoising and reconstruction tasks. For DRACO's pre-training, the quality of the dataset is essential, we hence build a high-quality, diverse dataset from an uncurated public database, including over 270,000 movies or micrographs. After pre-training, DRACO naturally serves as a generalizable cryo-EM image denoiser and a foundation model for various cryo-EM downstream tasks. DRACO demonstrates the best performance in denoising, micrograph curation, and particle picking tasks compared to state-of-the-art baselines. We will release the code, pre-trained models, and the curated dataset to stimulate further research.
