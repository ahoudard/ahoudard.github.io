---
title: "On the Existence of Optimal Transport Gradient for Learning Generative Models"
date: "2021-02-11"
categories: 
  - "paper"
---

##### **New preprint available!** \[[HAL](https://hal.archives-ouvertes.fr/hal-03137342)\] \[[PDF](https://hal.archives-ouvertes.fr/hal-03137342/document)\]\[[ArXiv](https://arxiv.org/abs/2102.05542)\]

![]({{ site.baseurl }}/images/image.png)

**Abstract** : The use of optimal transport cost for learning generative models has become popular with Wasserstein Generative Adversarial Networks (WGAN). Training of WGAN relies on a theoretical background: the calculation of the gradient of the optimal transport cost with respect to the generative model parameters. We first demonstrate that such gradient may not be defined, which can result in numerical instabilities during gradient-based optimization. We address this issue by stating a valid differentiation theorem in the case of entropic regularized transport and specify conditions under which existence is ensured. By exploiting the discrete nature of empirical data, we formulate the gradient in a semi-discrete setting and propose an algorithm for the optimization of the generative model parameters. Finally, we illustrate numerically the advantage of the proposed framework.
