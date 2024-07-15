---
title: High-Dimensional Geometric Streaming for Nearly Low Rank Data
openreview: yQfA0etfB7
abstract: We study streaming algorithms for the $\ell_p$ subspace approximation problem.
  Given points $a_1, \ldots, a_n$ as an insertion-only stream and a rank parameter
  $k$, the $\ell_p$ subspace approximation problem is to find a $k$-dimensional subspace
  $V$ such that $(\sum_{i=1}^n d(a_i, V)^p)^{1/p}$ is minimized, where $d(a, V)$ denotes
  the Euclidean distance between $a$ and $V$ defined as $\min_{v \in V} ||a - v||$.
  When $p = \infty$, we need to find a subspace $V$ that minimizes $\max_i d(a_i,
  V)$. For $\ell_{\infty}$ subspace approximation, we give a deterministic strong
  coreset construction algorithm and show that it can be used to compute a $\mathrm{poly}(k,
  \log n)$ approximate solution. We show that the distortion obtained by our coreset
  is nearly tight for any sublinear space algorithm. For $\ell_p$ subspace approximation,
  we show that suitably scaling the points and then using our $\ell_{\infty}$ coreset
  construction, we can compute a $\mathrm{poly}(k, \log n)$ approximation. Our algorithms
  are easy to implement and run very fast on large datasets. We also use our strong
  coreset construction to improve the results in a recent work of Woodruff and Yasuda
  (FOCS 2022) which gives streaming algorithms for high-dimensional geometric problems
  such as width estimation, convex hull estimation, and volume estimation.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: esfandiari24a
month: 0
tex_title: High-Dimensional Geometric Streaming for Nearly Low Rank Data
firstpage: 12588
lastpage: 12605
page: 12588-12605
order: 12588
cycles: false
bibtex_author: Esfandiari, Hossein and Kacham, Praneeth and Mirrokni, Vahab and Woodruff,
  David and Zhong, Peilin
author:
- given: Hossein
  family: Esfandiari
- given: Praneeth
  family: Kacham
- given: Vahab
  family: Mirrokni
- given: David
  family: Woodruff
- given: Peilin
  family: Zhong
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/esfandiari24a/esfandiari24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
