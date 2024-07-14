---
title: Simulation of Graph Algorithms with Looped Transformers
openreview: aA2326y3hf
abstract: The execution of graph algorithms using neural networks has recently attracted
  significant interest due to promising empirical progress. This motivates further
  understanding of how neural networks can replicate reasoning steps with relational
  data. In this work, we study the ability of transformer networks to simulate algorithms
  on graphs from a theoretical perspective. The architecture we use is a looped transformer
  with extra attention heads that interact with the graph. We prove by construction
  that this architecture can simulate individual algorithms such as Dijkstra’s shortest
  path, Breadth- and Depth-First Search, and Kosaraju’s strongly connected components,
  as well as multiple algorithms simultaneously. The number of parameters in the networks
  does not increase with the input graph size, which implies that the networks can
  simulate the above algorithms for any graph. Despite this property, we show a limit
  to simulation in our solution due to finite precision. Finally, we show a Turing
  Completeness result with constant width when the extra attention heads are utilized.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: back-de-luca24a
month: 0
tex_title: Simulation of Graph Algorithms with Looped Transformers
firstpage: 2319
lastpage: 2363
page: 2319-2363
order: 2319
cycles: false
bibtex_author: Back De Luca, Artur and Fountoulakis, Kimon
author:
- given: Artur
  family: Back De Luca
- given: Kimon
  family: Fountoulakis
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
pdf: https://proceedings.mlr.press/v235/assets/back-de-luca24a/back-de-luca24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
