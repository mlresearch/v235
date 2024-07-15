---
title: Estimating the Permanent by Nesting Importance Sampling
openreview: JVORowD4MD
abstract: Sequential importance sampling (SIS) is one of the prominent methods for
  estimating high-dimensional integrals. For example, it is empirically the most efficient
  method known for estimating the permanent of nonnegative matrices, a notorious problem
  with numerous applications in computer science, statistics, and other fields. Unfortunately,
  SIS typically fails to provide accuracy guarantees due to difficulties in bounding
  the variance of the importance weights; for estimating the permanent with accuracy
  guarantees, the most efficient practical methods known are based on rejection sampling.
  Taking the best of both worlds, we give a variant of SIS, in which sampling is proportional
  to the upper bound used in rejection sampling. We show that this method is provably
  more efficient than its rejection sampling counterpart, particularly in high accuracy
  regimes. On estimating the permanent, we empirically obtain up to two orders-of-magnitude
  speedups over a state-of-the-art rejection sampling method.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: harviainen24a
month: 0
tex_title: Estimating the Permanent by Nesting Importance Sampling
firstpage: 17657
lastpage: 17666
page: 17657-17666
order: 17657
cycles: false
bibtex_author: Harviainen, Juha and Koivisto, Mikko
author:
- given: Juha
  family: Harviainen
- given: Mikko
  family: Koivisto
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/harviainen24a/harviainen24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
