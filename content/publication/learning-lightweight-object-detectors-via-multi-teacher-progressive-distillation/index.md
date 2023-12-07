---
title: Learning Lightweight Object Detectors via Multi-Teacher Progressive
  Distillation
publication_types:
  - "1"
authors:
  - Shengcao Cao
  - Mengtian Li
  - James Hays
  - Deva Ramanan
  - Yi-Xiong Wang
  - Liang-Yan Gui
publication_short: In ICML 2023
abstract: Resource-constrained perception systems such as edge computing and
  vision-for-robotics require vision models to be both accurate and lightweight
  in computation and memory usage. While knowledge distillation is a proven
  strategy to enhance the performance of lightweight classification models, its
  application to structured outputs like object detection and instance
  segmentation remains a complicated task, due to the variability in outputs and
  complex internal network modules involved in the distillation process. In this
  paper, we propose a simple yet surprisingly effective sequential approach to
  knowledge distillation that progressively transfers the knowledge of a set of
  teacher detectors to a given lightweight student. To distill knowledge from a
  highly accurate but complex teacher model, we construct a sequence of teachers
  to help the student gradually adapt. Our progressive strategy can be easily
  combined with existing detection distillation mechanisms to consistently
  maximize student performance in various settings. To the best of our
  knowledge, we are the first to successfully distill knowledge from
  Transformer-based teacher detectors to convolution-based students, and
  unprecedentedly boost the performance of ResNet-50 based RetinaNet from 36.5%
  to 42.0% AP and Mask R-CNN from 38.2% to 42.5% AP on the MS COCO benchmark.
draft: false
featured: true
image:
  filename: mtpd-thumb.png
  focal_point: Smart
  preview_only: false
summary: Distill knowledge from an automatically designed sequence of teachers
  into a lightweight student object detector to mitigate the teacher-student
  capacity gap.
date: 2023-07-23T17:00:44.701Z
---
