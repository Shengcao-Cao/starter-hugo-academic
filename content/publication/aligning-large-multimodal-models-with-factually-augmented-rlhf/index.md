---
title: Aligning Large Multimodal Models with Factually Augmented RLHF
publication_types:
  - "3"
authors:
  - Zhiqing Sun
  - Sheng Shen
  - Shengcao Cao
  - Haotian Liu
  - Chunyuan Li
  - Yikang Shen
  - Chuang Gan
  - Liangyan Gui
  - Yu-Xiong Wang
  - Yiming Yang
  - Kurt Keutzer
  - Trevor Darrell
publication_short: Preprint
abstract: Large Multimodal Models (LMM) are built across modalities and the
  misalignment between two modalities can result in "hallucination", generating
  textual outputs that are not grounded by the multimodal information in
  context. To address the multimodal misalignment issue, we adapt the
  Reinforcement Learning from Human Feedback (RLHF) from the text domain to the
  vision-language alignment, where human annotators are asked to compare two
  responses and pinpoint the more hallucinated one, and the vision-language
  model is trained to maximize the simulated human rewards. We propose a new
  alignment algorithm called Factually Augmented RLHF that augments the reward
  model with additional factual information such as image captions and
  ground-truth multi-choice options, which alleviates the reward hacking
  phenomenon in RLHF and further improves the performance. We also enhance the
  GPT-4-generated training data (for vision instruction tuning) with previously
  available human-written image-text pairs to improve the general capabilities
  of our model. To evaluate the proposed approach in real-world scenarios, we
  develop a new evaluation benchmark MMHAL-BENCH with a special focus on
  penalizing hallucinations. As the first LMM trained with RLHF, our approach
  achieves remarkable improvement on the LLaVA-Bench dataset with the 96%
  performance level of the text-only GPT-4 (while previous best methods can only
  achieve the 87% level), and an improvement of 60% on MMHAL-BENCH over other
  baselines.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
summary: Learn large multimodal models with RLHF augmented by factual
  information to reduce hallucination.
date: 2023-09-25T18:00:33.684Z
url_pdf: "https://arxiv.org/abs/2309.14525"
url_code: "https://github.com/llava-rlhf/LLaVA-RLHF"
url_project: "https://llava-rlhf.github.io"
---
