---
title: A Rate-Distortion View of Uncertainty Quantification
openreview: zMGUDsPopK
abstract: In supervised learning, understanding an input’s proximity to the training
  data can help a model decide whether it has sufficient evidence for reaching a reliable
  prediction. While powerful probabilistic models such as Gaussian Processes naturally
  have this property, deep neural networks often lack it. In this paper, we introduce
  Distance Aware Bottleneck (DAB), i.e., a new method for enriching deep neural networks
  with this property. Building on prior information bottleneck approaches, our method
  learns a codebook that stores a compressed representation of all inputs seen during
  training. The distance of a new example from this codebook can serve as an uncertainty
  estimate for the example. The resulting model is simple to train and provides deterministic
  uncertainty estimates by a single forward pass. Finally, our method achieves better
  out-of-distribution (OOD) detection and misclassification prediction than prior
  methods, including expensive ensemble methods, deep kernel Gaussian Processes, and
  approaches based on the standard information bottleneck.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: apostolopoulou24a
month: 0
tex_title: A Rate-Distortion View of Uncertainty Quantification
firstpage: 1631
lastpage: 1654
page: 1631-1654
order: 1631
cycles: false
bibtex_author: Apostolopoulou, Ifigeneia and Eysenbach, Benjamin and Nielsen, Frank
  and Dubrawski, Artur
author:
- given: Ifigeneia
  family: Apostolopoulou
- given: Benjamin
  family: Eysenbach
- given: Frank
  family: Nielsen
- given: Artur
  family: Dubrawski
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/apostolopoulou24a/apostolopoulou24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
