---
title: Efficient Model Performance Estimation via Feature Histories
publication_types:
  - "3"
authors:
  - Shengcao Cao
  - Xiaofang Wang
  - Kris M. Kitani
publication_short: Preprint
abstract: "An important step in the task of neural network design, such as
  hyper-parameter optimization (HPO) or neural architecture search (NAS), is the
  evaluation of a candidate model's performance. Given fixed computational
  resources, one can either invest more time training each model to obtain more
  accurate estimates of final performance, or spend more time exploring a
  greater variety of models in the configuration space. In this work, we aim to
  optimize this exploration-exploitation trade-off in the context of HPO and NAS
  for image classification by accurately approximating a model's maximal
  performance early in the training process. In contrast to recent accelerated
  NAS methods customized for certain search spaces, e.g., requiring the search
  space to be differentiable, our method is flexible and imposes almost no
  constraints on the search space. Our method uses the evolution history of
  features of a network during the early stages of training to build a proxy
  classifier that matches the peak performance of the network under
  consideration. We show that our method can be combined with multiple search
  algorithms to find better solutions to a wide range of tasks in HPO and NAS.
  Using a sampling-based search algorithm and parallel computing, our method can
  find an architecture which is better than DARTS and with an 80% reduction in
  wall-clock search time. "
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
summary: Accelerate performance estimation for exploring new model
  configurations, improving neural achitecture search and hyper-parameter
  optimization within limited time.
date: 2021-03-07T18:00:32.887Z
url_pdf: "https://arxiv.org/abs/2103.04450"
---
