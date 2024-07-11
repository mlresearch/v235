---
title: 'Vectorized Conditional Neural Fields: A Framework for Solving Time-dependent
  Parametric Partial Differential Equations'
openreview: sF9epWkNUG
abstract: Transformer models are increasingly used for solving Partial Differential
  Equations (PDEs). Several adaptations have been proposed, all of which suffer from
  the typical problems of Transformers, such as quadratic memory and time complexity.
  Furthermore, all prevalent architectures for PDE solving lack at least one of several
  desirable properties of an ideal surrogate model, such as (i) generalization to
  PDE parameters not seen during training, (ii) spatial and temporal zero-shot super-resolution,
  (iii) continuous temporal extrapolation, (iv) support for 1D, 2D, and 3D PDEs, and
  (v) efficient inference for longer temporal rollouts. To address these limitations,
  we propose <em>Vectorized Conditional Neural Fields</em> (VCNeFs), which represent
  the solution of time-dependent PDEs as neural fields. Contrary to prior methods,
  however, VCNeFs compute, for a set of multiple spatio-temporal query points, their
  solutions in parallel and model their dependencies through attention mechanisms.
  Moreover, VCNeF can condition the neural field on both the initial conditions and
  the parameters of the PDEs. An extensive set of experiments demonstrates that VCNeFs
  are competitive with and often outperform existing ML-based surrogate models.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hagnberger24a
month: 0
tex_title: 'Vectorized Conditional Neural Fields: A Framework for Solving Time-dependent
  Parametric Partial Differential Equations'
firstpage: 17189
lastpage: 17223
page: 17189-17223
order: 17189
cycles: false
bibtex_author: Hagnberger, Jan and Kalimuthu, Marimuthu and Musekamp, Daniel and Niepert,
  Mathias
author:
- given: Jan
  family: Hagnberger
- given: Marimuthu
  family: Kalimuthu
- given: Daniel
  family: Musekamp
- given: Mathias
  family: Niepert
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
pdf: https://proceedings.mlr.press/v235/hagnberger24a/hagnberger24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
