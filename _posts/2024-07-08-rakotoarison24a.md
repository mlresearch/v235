---
title: In-Context Freeze-Thaw Bayesian Optimization for Hyperparameter Optimization
openreview: VyoY3Wh9Wd
abstract: With the increasing computational costs associated with deep learning, automated
  hyperparameter optimization methods, strongly relying on black-box Bayesian optimization
  (BO), face limitations. Freeze-thaw BO offers a promising grey-box alternative,
  strategically allocating scarce resources incrementally to different configurations.
  However, the frequent surrogate model updates inherent to this approach pose challenges
  for existing methods, requiring retraining or fine-tuning their neural network surrogates
  online, introducing overhead, instability, and hyper-hyperparameters. In this work,
  we propose FT-PFN, a novel surrogate for Freeze-thaw style BO. FT-PFN is a prior-data
  fitted network (PFN) that leverages the transformers’ in-context learning ability
  to efficiently and reliably do Bayesian learning curve extrapolation in a single
  forward pass. Our empirical analysis across three benchmark suites shows that the
  predictions made by FT-PFN are more accurate and 10-100 times faster than those
  of the deep Gaussian process and deep ensemble surrogates used in previous work.
  Furthermore, we show that, when combined with our novel acquisition mechanism (MFPI-random),
  the resulting in-context freeze-thaw BO method (ifBO), yields new state-of-the-art
  performance in the same three families of deep learning HPO benchmarks considered
  in prior work.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: rakotoarison24a
month: 0
tex_title: In-Context Freeze-Thaw {B}ayesian Optimization for Hyperparameter Optimization
firstpage: 41982
lastpage: 42008
page: 41982-42008
order: 41982
cycles: false
bibtex_author: Rakotoarison, Herilalaina and Adriaensen, Steven and Mallik, Neeratyoy
  and Garibov, Samir and Bergman, Eddie and Hutter, Frank
author:
- given: Herilalaina
  family: Rakotoarison
- given: Steven
  family: Adriaensen
- given: Neeratyoy
  family: Mallik
- given: Samir
  family: Garibov
- given: Eddie
  family: Bergman
- given: Frank
  family: Hutter
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
pdf: https://proceedings.mlr.press/v235/rakotoarison24a/rakotoarison24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
