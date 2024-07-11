---
title: Online Variational Sequential Monte Carlo
openreview: jbPc3pW6sC
abstract: Being the most classical generative model for serial data, state-space models
  (SSM) are fundamental in AI and statistical machine learning. In SSM, any form of
  parameter learning or latent state inference typically involves the computation
  of complex latent-state posteriors. In this work, we build upon the variational
  sequential Monte Carlo (VSMC) method, which provides computationally efficient and
  accurate model parameter estimation and Bayesian latent-state inference by combining
  particle methods and variational inference. While standard VSMC operates in the
  offline mode, by re-processing repeatedly a given batch of data, we distribute the
  approximation of the gradient of the VSMC surrogate ELBO in time using stochastic
  approximation, allowing for online learning in the presence of streams of data.
  This results in an algorithm, online VSMC, that is capable of performing efficiently,
  entirely on-the-fly, both parameter estimation and particle proposal adaptation.
  In addition, we provide rigorous theoretical results describing the algorithm’s
  convergence properties as the number of data tends to infinity as well as numerical
  illustrations of its excellent convergence properties and usefulness also in batch-processing
  settings.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mastrototaro24a
month: 0
tex_title: Online Variational Sequential {M}onte {C}arlo
firstpage: 35039
lastpage: 35062
page: 35039-35062
order: 35039
cycles: false
bibtex_author: Mastrototaro, Alessandro and Olsson, Jimmy
author:
- given: Alessandro
  family: Mastrototaro
- given: Jimmy
  family: Olsson
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
pdf: https://proceedings.mlr.press/v235/mastrototaro24a/mastrototaro24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
