---
title: Stationarity without mean reversion in improper Gaussian processes
openreview: 6CV1N7hhpA
abstract: The behavior of a GP regression depends on the choice of covariance function.
  Stationary covariance functions are preferred in machine learning applications.
  However, (non-periodic) stationary covariance functions are always mean reverting
  and can therefore exhibit pathological behavior when applied to data that does not
  relax to a fixed global mean value. In this paper we show that it is possible to
  use improper GP priors with infinite variance to define processes that are stationary
  but not mean reverting. To this aim, we use of non-positive kernels that can only
  be defined in this limit regime. The resulting posterior distributions can be computed
  analytically and it involves a simple correction of the usual formulas. The main
  contribution of the paper is the introduction of a large family of smooth non-reverting
  covariance functions that closely resemble the kernels commonly used in the GP literature
  (e.g. squared exponential and Matérn class). By analyzing both synthetic and real
  data, we demonstrate that these non-positive kernels solve some known pathologies
  of mean reverting GP regression while retaining most of the favorable properties
  of ordinary smooth stationary kernels.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ambrogioni24a
month: 0
tex_title: Stationarity without mean reversion in improper {G}aussian processes
firstpage: 1261
lastpage: 1275
page: 1261-1275
order: 1261
cycles: false
bibtex_author: Ambrogioni, Luca
author:
- given: Luca
  family: Ambrogioni
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
pdf: https://proceedings.mlr.press/v235/assets/ambrogioni24a/ambrogioni24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
