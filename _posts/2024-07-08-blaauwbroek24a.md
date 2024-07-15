---
title: 'Graph2Tac: Online Representation Learning of Formal Math Concepts'
openreview: A7CtiozznN
abstract: 'In proof assistants, the physical proximity between two formal mathematical
  concepts is a strong predictor of their mutual relevance. Furthermore, lemmas with
  close proximity regularly exhibit similar proof structures. We show that this <em>locality</em>
  property can be exploited through online learning techniques to obtain solving agents
  that far surpass offline learners when asked to prove theorems in an unseen mathematical
  setting. We extensively benchmark two such online solvers implemented in the Tactician
  platform for the Coq proof assistant: First, Tactician’s online $k$-nearest neighbor
  solver, which can learn from recent proofs, shows a $1.72\times$ improvement in
  theorems proved over an offline equivalent. Second, we introduce a graph neural
  network, Graph2Tac, with a novel approach to build hierarchical representations
  for new definitions. Graph2Tac’s online definition task realizes a $1.5\times$ improvement
  in theorems solved over an offline baseline. The $k$-NN and Graph2Tac solvers rely
  on orthogonal online data, making them highly complementary. Their combination improves
  $1.27\times$ over their individual performances. Both solvers outperform all other
  general purpose provers for Coq, including CoqHammer, Proverbot9001, and a transformer
  baseline by at least $1.48\times$ and are available for practical use by end-users.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: blaauwbroek24a
month: 0
tex_title: "{G}raph2{T}ac: Online Representation Learning of Formal Math Concepts"
firstpage: 4046
lastpage: 4076
page: 4046-4076
order: 4046
cycles: false
bibtex_author: Blaauwbroek, Lasse and Ol\v{s}\'{a}k, Mirek and Rute, Jason and Schaposnik
  Massolo, Fidel Ivan and Piepenbrock, Jelle and Pestun, Vasily
author:
- given: Lasse
  family: Blaauwbroek
- given: Mirek
  family: Olšák
- given: Jason
  family: Rute
- given: Fidel Ivan
  family: Schaposnik Massolo
- given: Jelle
  family: Piepenbrock
- given: Vasily
  family: Pestun
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/blaauwbroek24a/blaauwbroek24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
