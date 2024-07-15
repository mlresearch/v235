---
title: Dynamic Metric Embedding into lp Space
openreview: z3PUNzdmGs
abstract: 'We give the first non-trivial decremental dynamic embedding of a weighted,
  undirected graph $G$ into $\ell_p$ space. Given a weighted graph $G$ undergoing
  a sequence of edge weight increases, the goal of this problem is to maintain a (randomized)
  mapping $\phi: (G,d) \to (X,\ell_p)$ from the set of vertices of the graph to the
  $\ell_p$ space such that for every pair of vertices $u$ and $v$, the expected distance
  between $\phi(u)$ and $\phi(v)$ in the $\ell_p$ metric is within a small multiplicative
  factor, referred to as the distortion, of their distance in $G$. Our main result
  is a dynamic algorithm with expected distortion $O(\log^2 n)$ and total update time
  $O\left((m^{1+o(1)} \log^2 W + Q)\log(nW) \right)$, where $W$ is the maximum weight
  of the edges, $Q$ is the total number of updates and $n, m$ denote the number of
  vertices and edges in $G$ respectively. This is the first result of its kind, extending
  the seminal result of Bourgain ’85 to the expanding field of dynamic algorithms.
  Moreover, we demonstrate that in the fully dynamic regime, where we tolerate edge
  insertions as well as deletions, no algorithm can explicitly maintain an embedding
  into $\ell_p$ space that has a low distortion with high probability.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: banihashem24b
month: 0
tex_title: Dynamic Metric Embedding into lp Space
firstpage: 2831
lastpage: 2845
page: 2831-2845
order: 2831
cycles: false
bibtex_author: Banihashem, Kiarash and Hajiaghayi, Mohammadtaghi and Kowalski, Dariusz
  Rafal and Olkowski, Jan and Springer, Max
author:
- given: Kiarash
  family: Banihashem
- given: Mohammadtaghi
  family: Hajiaghayi
- given: Dariusz Rafal
  family: Kowalski
- given: Jan
  family: Olkowski
- given: Max
  family: Springer
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/banihashem24b/banihashem24b.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
