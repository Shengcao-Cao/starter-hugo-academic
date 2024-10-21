---
title: "Swiss Army Knife: Synergizing Biases in Knowledge from Vision Foundation
  Models for Multi-Task Learning"
publication_types:
  - "3"
authors:
  - Yuxiang Lu
  - Shengcao Cao
  - Yu-Xiong Wang
author_notes:
  - equal contribution
  - equal contribution
abstract: Vision Foundation Models (VFMs) have demonstrated outstanding
  performance on numerous downstream tasks. However, due to their inherent
  representation biases originating from different training paradigms, VFMs
  exhibit advantages and disadvantages across distinct vision tasks. Although
  amalgamating the strengths of multiple VFMs for downstream tasks is an
  intuitive strategy, effectively exploiting these biases remains a significant
  challenge. In this paper, we propose a novel and versatile "Swiss Army Knife"
  (SAK) solution, which adaptively distills knowledge from a committee of VFMs
  to enhance multi-task learning. Unlike existing methods that use a single
  backbone for knowledge transfer, our approach preserves the unique
  representation bias of each teacher by collaborating the lightweight
  Teacher-Specific Adapter Path modules with the Teacher-Agnostic Stem. Through
  dynamic selection and combination of representations with
  Mixture-of-Representations Routers, our SAK is capable of synergizing the
  complementary strengths of multiple VFMs. Extensive experiments show that our
  SAK remarkably outperforms prior state of the arts in multi-task learning by
  10% on the NYUD-v2 benchmark, while also providing a flexible and robust
  framework that can readily accommodate more advanced model designs.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2024-10-18T17:00:06.139Z
---
