---
title: "Learning local regularization for variational image restoration"
date: "2021-02-10"
categories: 
  - "paper"
---

##### **New preprint available!** \[[HAL](https://hal.archives-ouvertes.fr/hal-03139784)\] \[[PDF](https://arxiv.org/pdf/2102.06155.pdf)\]\[[ArXiv](https://arxiv.org/abs/2102.06155)\]

Joint work with Jean Prost, Andrés Almansa and Nicolas Papadakis

**Abstract:** In this work, we propose a framework to learn a local regularization model for solving general image restoration problems. This regularizer is defined with a fully convolutional neural network that sees the image through a receptive field corresponding to small image patches. The regularizer is then learned as a critic between unpaired distributions of clean and degraded patches using a Wasserstein generative adversarial networks based energy. This yields a regularization function that can be incorporated in any image restoration problem. The efficiency of the framework is finally shown on denoising and deblurring applications.
