---
title: Rethinking Transformer-Based Set Prediction for Object Detection
publication_types:
  - "1"
authors:
  - Zhiqing Sun
  - Shengcao Cao
  - Yiming Yang
  - Kris M. Kitani
author_notes:
  - equal contribution
  - equal contribution
publication_short: In ICCV 2021
abstract: "DETR is a recently proposed Transformer-based method which views
  object detection as a set prediction problem and achieves state-of-the-art
  performance but demands extra-long training time to converge. In this paper,
  we investigate the causes of the optimization difficulty in the training of
  DETR. Our examinations reveal several factors contributing to the slow
  convergence of DETR, primarily the issues with the Hungarian loss and the
  Transformer cross attention mechanism. To overcome these issues we propose two
  solutions, namely, TSP-FCOS (Transformer-based Set Prediction with FCOS) and
  TSP-RCNN (Transformer-based Set Prediction with RCNN). Experimental results
  show that the proposed methods not only converge much faster than the original
  DETR, but also significantly outperform DETR and other baselines in terms of
  detection accuracy. "
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
summary: Analyze the slow convergence of DEtection TRansformer (DETR), and
  propose alternative solutions to improve convergence and performance of DETR.
date: 2021-10-12T17:00:23.443Z
url_pdf: "https://arxiv.org/abs/2011.10881"
url_code: "https://github.com/Edward-Sun/TSP-Detection"
---
