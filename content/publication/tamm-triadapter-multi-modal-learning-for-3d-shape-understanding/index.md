---
title: "TAMM: TriAdapter Multi-Modal Learning for 3D Shape Understanding"
publication_types:
  - "1"
authors:
  - Zhihao Zhang
  - Shengcao Cao
  - Yu-Xiong Wang
author_notes:
  - equal contribution
  - equal contribution
publication_short: In CVPR 2024
abstract: "The limited scale of current 3D shape datasets hinders the
  advancements in 3D shape understanding and motivates multi-modal learning
  approaches which transfer learned knowledge from data-abundant 2D image and
  language modalities to 3D shapes. However even though the image and language
  representations have been aligned by cross-modal models like CLIP we find that
  the image modality fails to contribute as much as the language in existing
  multi-modal 3D representation learning methods. This is attributed to the
  domain shift in the 2D images and the distinct focus of each modality. To more
  effectively leverage both modalities in the pre-training we introduce
  TriAdapter Multi-Modal Learning (TAMM) - a novel two-stage learning approach
  based on three synergistic adapters. First our CLIP Image Adapter mitigates
  the domain gap between 3D-rendered images and natural images by adapting the
  visual representations of CLIP for synthetic image-text pairs. Subsequently
  our Dual Adapters decouple the 3D shape representation space into two
  complementary sub-spaces: one focusing on visual attributes and the other for
  semantic understanding which ensure a more comprehensive and effective
  multi-modal pre-training. Extensive experiments demonstrate that TAMM
  consistently enhances 3D representations for a wide range of 3D encoder
  architectures pre-training datasets and downstream tasks. Notably we boost the
  zero-shot classification accuracy on Objaverse-LVIS from 46.8% to 50.7% and
  improve the 5-way 10-shot linear probing classification accuracy on ModelNet40
  from 96.1% to 99.0%."
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
summary: Propose a multi-modal learning framework for 3D shapes with two learning
  stages and three unified adapter modules.
date: 2024-06-17T17:00:00.000Z
url_pdf: "https://arxiv.org/abs/2402.18490"
url_code: "https://github.com/alanzhangcs/Tamm_Code"
url_project: "https://alanzhangcs.github.io/tamm-page"
---
