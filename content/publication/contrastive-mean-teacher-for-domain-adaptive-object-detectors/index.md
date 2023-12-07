---
title: Contrastive Mean Teacher for Domain Adaptive Object Detectors
publication_types:
  - "1"
authors:
  - Shengcao Cao
  - Dhiraj Joshi
  - Liang-Yan Gui
  - Yu-Xiong Wang
publication_short: In CVPR 2023
abstract: "Object detectors often suffer from the domain gap between training
  (source domain) and real-world applications (target domain). Mean-teacher
  self-training is a powerful paradigm in unsupervised domain adaptation for
  object detection, but it struggles with low-quality pseudo-labels. In this
  work, we identify the intriguing alignment and synergy between mean-teacher
  self-training and contrastive learning. Motivated by this, we propose
  Contrastive Mean Teacher (CMT) -- a unified, general-purpose framework with
  the two paradigms naturally integrated to maximize beneficial learning
  signals. Instead of using pseudo-labels solely for final predictions, our
  strategy extracts object-level features using pseudo-labels and optimizes them
  via contrastive learning, without requiring labels in the target domain. When
  combined with recent mean-teacher self-training methods, CMT leads to new
  state-of-the-art target-domain performance: 51.9% mAP on Foggy Cityscapes,
  outperforming the previously best by 2.1% mAP. Notably, CMT can stabilize
  performance and provide more significant gains as pseudo-label noise
  increases. "
draft: false
featured: true
image:
  filename: teaser.png
  focal_point: Smart
  preview_only: false
summary: Unify contrastive learning for representation learning and Mean Teacher
  for domain adaptation into one general-purpose framework for learning
  unsupervised domain adaptive object detectors.
date: 2023-06-10T17:00:15.916Z
---
