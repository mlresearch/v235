---
title: 'PairNet: Training with Observed Pairs to Estimate Individual Treatment Effect'
openreview: o5SVr80Rgg
abstract: Given a dataset of individuals each described by a covariate vector, a treatment,
  and an observed outcome on the treatment, the goal of the individual treatment effect
  (ITE) estimation task is to predict outcome changes resulting from a change in treatment.
  A fundamental challenge is that in the observational data, a covariate’s outcome
  is observed only under one treatment, whereas we need to infer the difference in
  outcomes under two different treatments. Several existing approaches address this
  issue through training with inferred pseudo-outcomes, but their success relies on
  the quality of these pseudo-outcomes. We propose PairNet, a novel ITE estimation
  training strategy that minimizes losses over pairs of examples based on their factual
  observed outcomes. Theoretical analysis for binary treatments reveals that PairNet
  is a consistent estimator of ITE risk, and achieves smaller generalization error
  than baseline models. Empirical comparison with thirteen existing methods across
  eight benchmarks, covering both discrete and continuous treatments, shows that PairNet
  achieves significantly lower ITE error compared to the baselines. Also, it is model-agnostic
  and easy to implement.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: nagalapatti24a
month: 0
tex_title: "{P}air{N}et: Training with Observed Pairs to Estimate Individual Treatment
  Effect"
firstpage: 37237
lastpage: 37259
page: 37237-37259
order: 37237
cycles: false
bibtex_author: Nagalapatti, Lokesh and Singhal, Pranava and Ghosh, Avishek and Sarawagi,
  Sunita
author:
- given: Lokesh
  family: Nagalapatti
- given: Pranava
  family: Singhal
- given: Avishek
  family: Ghosh
- given: Sunita
  family: Sarawagi
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
pdf: https://proceedings.mlr.press/v235/nagalapatti24a/nagalapatti24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
