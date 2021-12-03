---
title: Neighborhood-Aware Neural Architecture Search
publication_types:
  - "1"
authors:
  - Xiaofang Wang
  - Shengcao Cao
  - Mengtian Li
  - Kris M. Kitani
publication_short: In BMVC 2021
abstract: "Existing neural architecture search (NAS) methods often return an
  architecture with good search performance but generalizes poorly to the test
  setting. To achieve better generalization, we propose a novel
  neighborhood-aware NAS formulation to identify flat-minima architectures in
  the search space, with the assumption that flat minima generalize better than
  sharp minima. The phrase ``flat-minima architecture'' refers to architectures
  whose performance is stable under small perturbations in the architecture
  (e.g., replacing a convolution with a skip connection). Our formulation takes
  the ``flatness'' of an architecture into account by aggregating the
  performance over the neighborhood of this architecture. We demonstrate a
  principled way to apply our formulation to existing search algorithms,
  including sampling-based algorithms and gradient-based algorithms. To
  facilitate the application to gradient-based algorithms, we also propose a
  differentiable representation for the neighborhood of architectures. Based on
  our formulation, we propose neighborhood-aware random search (NA-RS) and
  neighborhood-aware differentiable architecture search (NA-DARTS). Notably, by
  simply augmenting DARTS with our formulation, NA-DARTS outperforms DARTS and
  achieves state-of-the-art performance on established benchmarks, including
  CIFAR-10, CIFAR-100 and ImageNet. "
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
summary: Propose a novel neural architecture search formulation to encourage
  flatness in the architecture space, which improves generalization of searched
  architectures.
date: 2021-10-29T17:00:05.432Z
---
