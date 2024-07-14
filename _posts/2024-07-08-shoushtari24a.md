---
title: Prior Mismatch and Adaptation in PnP-ADMM with a Nonconvex Convergence Analysis
openreview: AYWBRwsZ8z
abstract: Plug-and-Play (PnP) priors is a widely-used family of methods for solving
  imaging inverse problems by integrating physical measurement models with image priors
  specified using image denoisers. PnP methods have been shown to achieve state-of-the-art
  performance when the prior is obtained using powerful deep denoisers. Despite extensive
  work on PnP, the topic of distribution mismatch between the training and testing
  data has often been overlooked in the PnP literature. This paper presents a set
  of new theoretical and numerical results on the topic of prior distribution mismatch
  and domain adaptation for the alternating direction method of multipliers (ADMM)
  variant of PnP. Our theoretical result provides an explicit error bound for PnP-ADMM
  due to the mismatch between the desired denoiser and the one used for inference.
  Our analysis contributes to the work in the area by considering the mismatch under
  nonconvex data-fidelity terms and expansive denoisers. Our first set of numerical
  results quantifies the impact of the prior distribution mismatch on the performance
  of PnP-ADMM on the problem of image super-resolution. Our second set of numerical
  results considers a simple and effective domain adaption strategy that closes the
  performance gap due to the use of mismatched denoisers. Our results suggest the
  relative robustness of PnP-ADMM to prior distribution mismatch, while also showing
  that the performance gap can be significantly reduced with only a few training samples
  from the desired distribution.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: shoushtari24a
month: 0
tex_title: Prior Mismatch and Adaptation in {P}n{P}-{ADMM} with a Nonconvex Convergence
  Analysis
firstpage: 45154
lastpage: 45182
page: 45154-45182
order: 45154
cycles: false
bibtex_author: Shoushtari, Shirin and Liu, Jiaming and Chandler, Edward P. and Asif,
  M. Salman and Kamilov, Ulugbek S.
author:
- given: Shirin
  family: Shoushtari
- given: Jiaming
  family: Liu
- given: Edward P.
  family: Chandler
- given: M. Salman
  family: Asif
- given: Ulugbek S.
  family: Kamilov
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
pdf: https://proceedings.mlr.press/v235/assets/shoushtari24a/shoushtari24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
