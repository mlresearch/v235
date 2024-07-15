---
title: 'Lessons from Generalization Error Analysis of Federated Learning: You May
  Communicate Less Often!'
openreview: ffS0aYP6mk
abstract: We investigate the generalization error of statistical learning models in
  a Federated Learning (FL) setting. Specifically, we study the evolution of the generalization
  error with the number of communication rounds $R$ between $K$ clients and a parameter
  server (PS), i.e. the effect on the generalization error of how often the clients’
  local models are aggregated at PS. In our setup, the more the clients communicate
  with PS the less data they use for local training in each round, such that the amount
  of training data per client is identical for distinct values of $R$. We establish
  PAC-Bayes and rate-distortion theoretic bounds on the generalization error that
  account explicitly for the effect of the number of rounds $R$, in addition to the
  number of participating devices $K$ and individual datasets size $n$. The bounds,
  which apply to a large class of loss functions and learning algorithms, appear to
  be the first of their kind for the FL setting. Furthermore, we apply our bounds
  to FL-type Support Vector Machines (FSVM); and derive (more) explicit bounds in
  this case. In particular, we show that the generalization bound of FSVM increases
  with $R$, suggesting that more frequent communication with PS diminishes the generalization
  power. This implies that the population risk decreases less fast with $R$ than does
  the empirical risk. Moreover, our bound suggests that the generalization error of
  FSVM decreases faster than that of centralized learning by a factor of $\mathcal{O}(\sqrt{\log(K)/K})$.
  Finally, we provide experimental results obtained using neural networks (ResNet-56)
  which show evidence that not only may our observations for FSVM hold more generally
  but also that the population risk may even start to increase beyond some value of
  $R$.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sefidgaran24a
month: 0
tex_title: 'Lessons from Generalization Error Analysis of Federated Learning: You
  May Communicate Less Often!'
firstpage: 44093
lastpage: 44135
page: 44093-44135
order: 44093
cycles: false
bibtex_author: Sefidgaran, Milad and Chor, Romain and Zaidi, Abdellatif and Wan, Yijun
author:
- given: Milad
  family: Sefidgaran
- given: Romain
  family: Chor
- given: Abdellatif
  family: Zaidi
- given: Yijun
  family: Wan
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/sefidgaran24a/sefidgaran24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
