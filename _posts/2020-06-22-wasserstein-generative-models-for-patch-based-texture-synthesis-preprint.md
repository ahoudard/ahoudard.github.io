---
title: "Wasserstein Generative Models for Patch-based Texture Synthesis"
date: "2020-06-22"
categories: 
  - "paper"
---

#### Wasserstein Generative Models for Patch-based Texture Synthesis \[[arXiv](https://arxiv.org/abs/2007.03408)\] \[[HAL](https://hal.archives-ouvertes.fr/hal-02824076v2/document)\]

**NEW! Published at SSVM 2021 \[[link](https://link.springer.com/chapter/10.1007/978-3-030-75549-2_22)\]**

###### joint work with Arthur Leclaire, Nicolas Papadakis and Julien Rabin

[![]({{ site.baseurl }}/images/textures.png)](https://houdard.wp.imt.fr/files/2020/06/textures.png)

**Abstract:** In this paper, we propose a framework to train a generative model for texture imagesynthesis from a single example. To do so, we exploit the local representationof images via the space of patches, that is, square sub-images of fixed size (e.g. 4×4). Our main contribution is to consider optimal transport to enforce themultiscale patch distribution of generated images, which leads to two differentformulations. First, a pixel-based optimization method is proposed, relying ondiscrete optimal transport. We show that it is related to a well-known textureoptimization framework based on iterated patch nearest-neighbor projections, whileavoiding some of its shortcomings. Second, in a semi-discrete setting, we exploitthe differential properties of Wasserstein distances to learn a fully convolutionalnetwork for texture generation. Once estimated, this network produces realisticand arbitrarily large texture samples in real time. The two formulations result innon-convex concave problems that can be optimized efficiently with convergenceproperties and improved stability compared to adversarial approaches, withoutrelying on any regularization. By directly dealing with the patch distribution ofsynthesized images, we also overcome limitations of state-of-the art techniques,such as patch aggregation issues that usually lead to low frequency artifacts (e.g. blurring) in traditional patch-based approaches, or statistical inconsistencies (e.g. color or patterns) in learning approaches.
