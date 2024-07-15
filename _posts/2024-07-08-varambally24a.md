---
title: Discovering Mixtures of Structural Causal Models from Time Series Data
openreview: cHJAUdam3i
abstract: 'Discovering causal relationships from time series data is significant in
  fields such as finance, climate science, and neuroscience. However, contemporary
  techniques rely on the simplifying assumption that data originates from the same
  causal model, while in practice, data is heterogeneous and can stem from different
  causal models. In this work, we relax this assumption and perform causal discovery
  from time series data originating from <em>a mixture of causal models</em>. We propose
  a general variational inference-based framework called MCD to infer the underlying
  causal models as well as the mixing probability of each sample. Our approach employs
  an end-to-end training process that maximizes an evidence-lower bound for the data
  likelihood. We present two variants: MCD-Linear for linear relationships and independent
  noise, and MCD-Nonlinear for nonlinear causal relationships and history-dependent
  noise. We demonstrate that our method surpasses state-of-the-art benchmarks in causal
  discovery tasks through extensive experimentation on synthetic and real-world datasets,
  particularly when the data emanates from diverse underlying causal graphs. Theoretically,
  we prove the identifiability of such a model under some mild assumptions. Implementation
  is available at https://github.com/Rose-STL-Lab/MCD.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: varambally24a
month: 0
tex_title: Discovering Mixtures of Structural Causal Models from Time Series Data
firstpage: 49171
lastpage: 49202
page: 49171-49202
order: 49171
cycles: false
bibtex_author: Varambally, Sumanth and Ma, Yian and Yu, Rose
author:
- given: Sumanth
  family: Varambally
- given: Yian
  family: Ma
- given: Rose
  family: Yu
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/varambally24a/varambally24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
