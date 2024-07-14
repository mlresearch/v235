---
title: Fair Federated Learning via the Proportional Veto Core
openreview: 6Zgjrowepn
abstract: Previous work on fairness in federated learning introduced the notion of
  <em>core stability</em>, which provides utility-based fairness guarantees to any
  subset of participating agents. However, these guarantees require strong assumptions
  on agent utilities that render them impractical. To address this shortcoming, we
  measure the quality of output models in terms of their ordinal <em>rank</em> instead
  of their cardinal utility, and use this insight to adapt the classical notion of
  <em>proportional veto core (PVC)</em> from social choice theory to the federated
  learning setting. We prove that models that are <em>PVC-stable</em> exist in very
  general learning paradigms, even allowing non-convex model sets, as well as non-convex
  and non-concave loss functions. We also design Rank-Core-Fed, a distributed federated
  learning algorithm, to train a PVC-stable model. Finally, we demonstrate that Rank-Core-Fed
  outperforms baselines in terms of fairness on different datasets.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ray-chaudhury24a
month: 0
tex_title: Fair Federated Learning via the Proportional Veto Core
firstpage: 42245
lastpage: 42257
page: 42245-42257
order: 42245
cycles: false
bibtex_author: Ray Chaudhury, Bhaskar and Murhekar, Aniket and Yuan, Zhuowen and Li,
  Bo and Mehta, Ruta and Procaccia, Ariel D.
author:
- given: Bhaskar
  family: Ray Chaudhury
- given: Aniket
  family: Murhekar
- given: Zhuowen
  family: Yuan
- given: Bo
  family: Li
- given: Ruta
  family: Mehta
- given: Ariel D.
  family: Procaccia
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
pdf: https://proceedings.mlr.press/v235/assets/ray-chaudhury24a/ray-chaudhury24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
