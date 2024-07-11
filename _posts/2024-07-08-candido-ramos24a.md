---
title: Mimicking Better by Matching the Approximate Action Distribution
openreview: JAfIDm7NED
abstract: In this paper, we introduce MAAD, a novel, sample-efficient on-policy algorithm
  for Imitation Learning from Observations. MAAD utilizes a surrogate reward signal,
  which can be derived from various sources such as adversarial games, trajectory
  matching objectives, or optimal transport criteria. To compensate for the non-availability
  of expert actions, we rely on an inverse dynamics model that infers plausible actions
  distribution given the expert’s state-state transitions; we regularize the imitator’s
  policy by aligning it to the inferred action distribution. MAAD leads to significantly
  improved sample efficiency and stability. We demonstrate its effectiveness in a
  number of MuJoCo environments, both int the OpenAI Gym and the DeepMind Control
  Suite. We show that it requires considerable fewer interactions to achieve expert
  performance, outperforming current state-of-the-art on-policy methods. Remarkably,
  MAAD often stands out as the sole method capable of attaining expert performance
  levels, underscoring its simplicity and efficacy.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: candido-ramos24a
month: 0
tex_title: Mimicking Better by Matching the Approximate Action Distribution
firstpage: 5513
lastpage: 5532
page: 5513-5532
order: 5513
cycles: false
bibtex_author: Candido Ramos, Joao and Blond\'{e}, Lionel and Takeishi, Naoya and
  Kalousis, Alexandros
author:
- given: Joao
  family: Candido Ramos
- given: Lionel
  family: Blondé
- given: Naoya
  family: Takeishi
- given: Alexandros
  family: Kalousis
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
pdf: https://proceedings.mlr.press/v235/candido-ramos24a/candido-ramos24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
