---
title: Graph Neural Networks Use Graphs When They Shouldn’t
openreview: fSNHK7mu3j
abstract: Predictions over graphs play a crucial role in various domains, including
  social networks and medicine. Graph Neural Networks (GNNs) have emerged as the dominant
  approach for learning on graph data. Although a graph-structure is provided as input
  to the GNN, in some cases the best solution can be obtained by ignoring it. While
  GNNs have the ability to ignore the graph-structure in such cases, it is not clear
  that they will. In this work, we show that GNNs actually tend to overfit the given
  graph-structure in the sense that they use it even when a better solution can be
  obtained by ignoring it. We analyze the implicit bias of gradient-descent learning
  of GNNs and prove that when the ground truth function does not use the graphs, GNNs
  are not guaranteed to learn a solution that ignores the graph, even with infinite
  data. We examine this phenomenon with respect to different graph distributions and
  find that regular graphs are more robust to this overfitting. We also prove that
  within the family of regular graphs, GNNs are guaranteed to extrapolate when learning
  with gradient descent. Finally, based on our empirical and theoretical findings,
  we demonstrate on real-data how regular graphs can be leveraged to reduce graph
  overfitting and enhance performance.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bechler-speicher24a
month: 0
tex_title: Graph Neural Networks Use Graphs When They Shouldn’t
firstpage: 3284
lastpage: 3304
page: 3284-3304
order: 3284
cycles: false
bibtex_author: Bechler-Speicher, Maya and Amos, Ido and Gilad-Bachrach, Ran and Globerson,
  Amir
author:
- given: Maya
  family: Bechler-Speicher
- given: Ido
  family: Amos
- given: Ran
  family: Gilad-Bachrach
- given: Amir
  family: Globerson
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
pdf: https://proceedings.mlr.press/v235/assets/bechler-speicher24a/bechler-speicher24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
