---
title: 'SPADE: Sparsity-Guided Debugging for Deep Neural Networks'
openreview: oBYv73nOoA
abstract: It is known that sparsity can improve interpretability for deep neural networks.
  However, existing methods in the area either require networks that are pre-trained
  with sparsity constraints, or impose sparsity after the fact, altering the network’s
  general behavior. In this paper, we demonstrate, for the first time, that sparsity
  can instead be incorporated into the interpretation process itself, as a sample-specific
  preprocessing step. Unlike previous work, this approach, which we call SPADE, does
  not place constraints on the trained model and does not affect its behavior during
  inference on the sample. Given a trained model and a target sample, SPADE uses sample-targeted
  pruning to provide a "trace" of the network’s execution on the sample, reducing
  the network to the most important connections prior to computing an interpretation.
  We demonstrate that preprocessing with SPADE significantly increases the accuracy
  of image saliency maps across several interpretability methods. Additionally, SPADE
  improves the usefulness of neuron visualizations, aiding humans in reasoning about
  network behavior. Our code is available at https://github.com/IST-DASLab/SPADE.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: soltani-moakhar24a
month: 0
tex_title: "{SPADE}: Sparsity-Guided Debugging for Deep Neural Networks"
firstpage: 45955
lastpage: 45987
page: 45955-45987
order: 45955
cycles: false
bibtex_author: Soltani Moakhar, Arshia and Iofinova, Eugenia and Frantar, Elias and
  Alistarh, Dan
author:
- given: Arshia
  family: Soltani Moakhar
- given: Eugenia
  family: Iofinova
- given: Elias
  family: Frantar
- given: Dan
  family: Alistarh
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
pdf: https://proceedings.mlr.press/v235/soltani-moakhar24a/soltani-moakhar24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
