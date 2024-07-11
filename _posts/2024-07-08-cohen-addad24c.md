---
title: A Near-Linear Time Approximation Algorithm for Beyond-Worst-Case Graph Clustering
openreview: MSFxOMM0gK
abstract: We consider the semi-random graph model of [Makarychev, Makarychev and Vijayaraghavan,
  STOC’12], where, given a random bipartite graph with $\alpha$ edges and an unknown
  bipartition $(A, B)$ of the vertex set, an adversary can add arbitrary edges inside
  each community and remove arbitrary edges from the cut $(A, B)$ (i.e. all adversarial
  changes are <em>monotone</em> with respect to the bipartition). For this model,
  a polynomial time algorithm [MMV’12] is known to approximate the Balanced Cut problem
  up to value $O(\alpha)$ as long as the cut $(A, B)$ has size $\Omega(\alpha)$. However,
  it consists of slow subroutines requiring optimal solutions for logarithmically
  many semidefinite programs. We study the fine-grained complexity of the problem
  and present the first near-linear time algorithm that achieves similar performances
  to that of [MMV’12]. Our algorithm runs in time $O(|V(G)|^{1+o(1)} + |E(G)|^{1+o(1)})$
  and finds a balanced cut of value $O(\alpha).$ Our approach appears easily extendible
  to related problem, such as Sparsest Cut, and also yields an near-linear time $O(1)$-approximation
  to Dagupta’s objective function for hierarchical clustering [Dasgupta, STOC’16]
  for the semi-random hierarchical stochastic block model inputs of [Cohen-Addad,
  Kanade, Mallmann-Trenn, Mathieu, JACM’19].
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: cohen-addad24c
month: 0
tex_title: A Near-Linear Time Approximation Algorithm for Beyond-Worst-Case Graph
  Clustering
firstpage: 9208
lastpage: 9229
page: 9208-9229
order: 9208
cycles: false
bibtex_author: Cohen-Addad, Vincent and D'Orsi, Tommaso and Mousavifar, Aida
author:
- given: Vincent
  family: Cohen-Addad
- given: Tommaso
  family: D’Orsi
- given: Aida
  family: Mousavifar
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
pdf: https://proceedings.mlr.press/v235/cohen-addad24c/cohen-addad24c.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
