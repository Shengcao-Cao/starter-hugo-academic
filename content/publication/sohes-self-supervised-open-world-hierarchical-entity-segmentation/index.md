---
title: "SOHES: Self-supervised Open-world Hierarchical Entity Segmentation"
publication_types:
  - "1"
authors:
  - Shengcao Cao
  - Jiuxiang Gu
  - Jason Kuen
  - Hao Tan
  - Ruiyi Zhang
  - Handong Zhao
  - Ani Nenkova
  - Liang-Yan Gui
  - Tong Sun
  - Yu-Xiong Wang
publication_short: In ICLR 2024
abstract: "Open-world entity segmentation, as an emerging computer vision task,
  aims at segmenting entities in images without being restricted by pre-defined
  classes, offering impressive generalization capabilities on unseen images and
  concepts. Despite its promise, existing entity segmentation methods like
  Segment Anything Model (SAM) rely heavily on costly expert annotators. This
  work presents Self-supervised Open-world Hierarchical Entity Segmentation
  (SOHES), a novel approach that sidesteps the need for human annotations. SOHES
  operates in three phases: self-exploration, self-instruction, and
  self-correction. Given a pre-trained self-supervised representation, we
  produce abundant high-quality pseudo-labels through visual feature clustering.
  Then, we train a segmentation model on the pseudo-labels, and rectify the
  noises in pseudo-labels via a teacher-student mutual-learning procedure.
  Beyond segmenting entities, SOHES also captures their constituent parts,
  providing a hierarchical understanding of visual entities. Using raw images as
  the sole training data, our method achieves unprecedented performance in
  self-supervised open-world segmentation, marking a significant milestone
  towards high-quality open-world entity segmentation in the absence of
  human-annotated masks."
draft: false
featured: true
image:
  filename: sohes-teaser-new.png
  focal_point: Smart
  preview_only: false
summary: Learn to segment visual entities and their parts in an open-world
  with pure self-supervision.
date: 2024-02-18T22:02:14.714Z
url_pdf: "https://arxiv.org/abs/2404.12386"
url_project: "https://sohes.github.io"
url_video: "https://www.youtube.com/watch?v=Q558YOmF7Zg"
---
