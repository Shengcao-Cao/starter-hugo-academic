---
title: Learnable Embedding Space for Efficient Neural Architecture Compression
publication_types:
  - "1"
authors:
  - **Shengcao Cao\***
  - Xiaofang Wang\*
  - Kris M. Kitani
publication_short: In ICLR 2019
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
abstract: We propose a method to incrementally learn an embedding space over the domain of network architectures, to enable the careful selection of architectures for evaluation during compressed architecture search. Given a teacher network, we search for a compressed network architecture by using Bayesian Optimization (BO) with a kernel function defined over our proposed embedding space to select architectures for evaluation. We demonstrate that our search algorithm can significantly outperform various baseline methods, such as random search and reinforcement learning (Ashok et al., 2018). The compressed architectures found by our method are also better than the state-of-the-art manually-designed compact architecture ShuffleNet (Zhang et al., 2018). We also demonstrate that the learned embedding space can be transferred to new settings for architecture search, such as a larger teacher network or a teacher network in a different architecture family, without any training.
summary: Search compressed network architectures in a learnable embedding space
  via Bayesian optimization, and find compressed networks outperforming
  hand-crafted architectures.
date: 2019-04-25T17:00:00.000Z
url_pdf: "https://arxiv.org/abs/1902.00383"
url_code: "https://github.com/Friedrich1006/ESNAC"
---
