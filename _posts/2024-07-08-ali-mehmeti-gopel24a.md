---
title: On the Weight Dynamics of Deep Normalized Networks
openreview: AzUCfhJ9Bs
abstract: Recent studies have shown that high disparities in effective learning rates
  (ELRs) across layers in deep neural networks can negatively affect trainability.
  We formalize how these disparities evolve over time by modeling weight dynamics
  (evolution of expected gradient and weight norms) of networks with normalization
  layers, predicting the evolution of layer-wise ELR ratios. We prove that when training
  with any constant learning rate, ELR ratios converge to 1, despite initial gradient
  explosion. We identify a "critical learning rate" beyond which ELR disparities widen,
  which only depends on current ELRs. To validate our findings, we devise a hyper-parameter-free
  warm-up method that successfully minimizes ELR spread quickly in theory and practice.
  Our experiments link ELR spread with trainability, a relationship that is most evident
  in very deep networks with significant gradient magnitude excursions.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ali-mehmeti-gopel24a
month: 0
tex_title: On the Weight Dynamics of Deep Normalized Networks
firstpage: 992
lastpage: 1007
page: 992-1007
order: 992
cycles: false
bibtex_author: Ali Mehmeti-G\"{o}pel, Christian H.X. and Wand, Michael
author:
- given: Christian H.X.
  family: Ali Mehmeti-Göpel
- given: Michael
  family: Wand
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
pdf: https://proceedings.mlr.press/v235/ali-mehmeti-gopel24a/ali-mehmeti-gopel24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
