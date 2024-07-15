---
title: 'No Wrong Turns: The Simple Geometry Of Neural Networks Optimization Paths'
openreview: 60vx5AfM3C
abstract: Understanding the optimization dynamics of neural networks is necessary
  for closing the gap between theory and practice. Stochastic first-order optimization
  algorithms are known to efficiently locate favorable minima in deep neural networks.
  This efficiency, however, contrasts with the non-convex and seemingly complex structure
  of neural loss landscapes. In this study, we delve into the fundamental geometric
  properties of sampled gradients along optimization paths. We focus on two key quantities,
  the restricted secant inequality and error bound, as well as their ratio γ, which
  hold high significance for first-order optimization. Our analysis reveals that these
  quantities exhibit predictable, consistent behavior throughout training, despite
  the stochasticity induced by sampling minibatches. Our findings suggest that not
  only do optimization trajectories never encounter significant obstacles, but they
  also maintain stable dynamics during the majority of training. These observed properties
  are sufficiently expressive to theoretically guarantee linear convergence and prescribe
  learning rate schedules mirroring empirical practices. We conduct our experiments
  on image classification, semantic segmentation and language modeling across different
  batch sizes, network architectures, datasets, optimizers, and initialization seeds.
  We discuss the impact of each factor. Our work provides novel insights into the
  properties of neural network loss functions, and opens the door to theoretical frameworks
  more relevant to prevalent practice.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: guille-escuret24a
month: 0
tex_title: 'No Wrong Turns: The Simple Geometry Of Neural Networks Optimization Paths'
firstpage: 16751
lastpage: 16772
page: 16751-16772
order: 16751
cycles: false
bibtex_author: Guille-Escuret, Charles and Naganuma, Hiroki and Fatras, Kilian and
  Mitliagkas, Ioannis
author:
- given: Charles
  family: Guille-Escuret
- given: Hiroki
  family: Naganuma
- given: Kilian
  family: Fatras
- given: Ioannis
  family: Mitliagkas
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/guille-escuret24a/guille-escuret24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
