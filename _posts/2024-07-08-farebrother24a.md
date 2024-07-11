---
title: 'Stop Regressing: Training Value Functions via Classification for Scalable
  Deep RL'
openreview: dVpFKfqF3R
abstract: 'Value functions are an essential component in deep reinforcement learning
  (RL), that are typically trained via mean squared error regression to match bootstrapped
  target values. However, scaling value-based RL methods to large networks has proven
  challenging. This difficulty is in stark contrast to supervised learning: by leveraging
  a cross-entropy classification loss, supervised methods have scaled reliably to
  massive networks. Observing this discrepancy, in this paper, we investigate whether
  the scalability of deep RL can also be improved simply by using classification in
  place of regression for training value functions. We show that training value functions
  with categorical cross-entropy significantly enhances performance and scalability
  across various domains, including single-task RL on Atari 2600 games, multi-task
  RL on Atari with large-scale ResNets, robotic manipulation with Q-transformers,
  playing Chess without search, and a language-agent Wordle task with high-capacity
  Transformers, achieving <em>state-of-the-art results</em> on these domains. Through
  careful analysis, we show that categorical cross-entropy mitigates issues inherent
  to value-based RL, such as noisy targets and non-stationarity. We argue that shifting
  to categorical cross-entropy for training value functions can substantially improve
  the scalability of deep RL at little-to-no cost.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: farebrother24a
month: 0
tex_title: 'Stop Regressing: Training Value Functions via Classification for Scalable
  Deep {RL}'
firstpage: 13049
lastpage: 13071
page: 13049-13071
order: 13049
cycles: false
bibtex_author: Farebrother, Jesse and Orbay, Jordi and Vuong, Quan and Ali Taiga,
  Adrien and Chebotar, Yevgen and Xiao, Ted and Irpan, Alex and Levine, Sergey and
  Castro, Pablo Samuel and Faust, Aleksandra and Kumar, Aviral and Agarwal, Rishabh
author:
- given: Jesse
  family: Farebrother
- given: Jordi
  family: Orbay
- given: Quan
  family: Vuong
- given: Adrien
  family: Ali Taiga
- given: Yevgen
  family: Chebotar
- given: Ted
  family: Xiao
- given: Alex
  family: Irpan
- given: Sergey
  family: Levine
- given: Pablo Samuel
  family: Castro
- given: Aleksandra
  family: Faust
- given: Aviral
  family: Kumar
- given: Rishabh
  family: Agarwal
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
pdf: https://proceedings.mlr.press/v235/farebrother24a/farebrother24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
