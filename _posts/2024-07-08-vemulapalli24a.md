---
title: Knowledge Transfer from Vision Foundation Models for Efficient Training of
  Small Task-specific Models
openreview: OKYfaYQlML
abstract: Vision Foundation Models (VFMs) pretrained on massive datasets exhibit impressive
  performance on various downstream tasks, especially with limited labeled target
  data. However, due to their high inference compute cost, these models cannot be
  deployed for many real-world applications. Motivated by this, we ask the following
  important question, "How can we leverage the knowledge from a large VFM to train
  a small task-specific model for a new target task with limited labeled training
  data?", and propose a simple task-oriented knowledge transfer approach as a highly
  effective solution to this problem. Our experimental results on five target tasks
  show that the proposed approach outperforms task-agnostic VFM distillation, web-scale
  CLIP pretraining, supervised ImageNet pretraining, and self-supervised DINO pretraining
  by up to 11.6%, 22.1%, 13.7%, and 29.8%, respectively. Furthermore, the proposed
  approach also demonstrates up to 9x, 4x and 15x reduction in pretraining compute
  cost when compared to task-agnostic VFM distillation, ImageNet pretraining and DINO
  pretraining, respectively, while outperforming them. We also show that the dataset
  used for transferring knowledge has a significant effect on the final target task
  performance, and introduce a retrieval-augmented knowledge transfer strategy that
  uses web-scale image retrieval to curate effective transfer sets.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: vemulapalli24a
month: 0
tex_title: Knowledge Transfer from Vision Foundation Models for Efficient Training
  of Small Task-specific Models
firstpage: 49345
lastpage: 49367
page: 49345-49367
order: 49345
cycles: false
bibtex_author: Vemulapalli, Raviteja and Pouransari, Hadi and Faghri, Fartash and
  Mehta, Sachin and Farajtabar, Mehrdad and Rastegari, Mohammad and Tuzel, Oncel
author:
- given: Raviteja
  family: Vemulapalli
- given: Hadi
  family: Pouransari
- given: Fartash
  family: Faghri
- given: Sachin
  family: Mehta
- given: Mehrdad
  family: Farajtabar
- given: Mohammad
  family: Rastegari
- given: Oncel
  family: Tuzel
date: 2024-07-08
address:
container-title: Proceedings of the 41st International Conference on Machine Learning
volume: '235'
genre: inproceedings
issued:
  date-parts:
  - 2024
  - 7
  - 8
pdf: https://proceedings.mlr.press/v235/vemulapalli24a/vemulapalli24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
