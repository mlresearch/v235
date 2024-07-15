---
title: Human Alignment of Large Language Models through Online Preference Optimisation
openreview: 2RQqg2Y7Y6
abstract: Ensuring alignment of language model’s outputs with human preferences is
  critical to guarantee a useful, safe, and pleasant user experience. Thus, human
  alignment has been extensively studied recently and several methods such as Reinforcement
  Learning from Human Feedback (RLHF), Direct Policy Optimisation (DPO) and Sequence
  Likelihood Calibration (SLiC) have emerged. In this paper, our contribution is two-fold.
  First, we show the equivalence between two recent alignment methods, namely Identity
  Policy Optimisation (IPO) and Nash Mirror Descent (Nash-MD). Second, we introduce
  a generalisation of IPO, named IPO-MD, that leverages the regularised sampling approach
  proposed by Nash-MD. This equivalence may seem surprising at first sight, since
  IPO is an offline method whereas Nash-MD is an online method using a preference
  model. However, this equivalence can be proven when we consider the online version
  of IPO, that is when both generations are sampled by the online policy and annotated
  by a trained preference model. Optimising the IPO loss with such a stream of data
  becomes then equivalent to finding the Nash equilibrium of the preference model
  through self-play. Building on this equivalence, we introduce the IPO-MD algorithm
  that generates data with a mixture policy (between the online and reference policy)
  similarly as the general Nash-MD algorithm. We compare online-IPO and IPO-MD to
  different online versions of existing losses on preference data such as DPO and
  SLiC on a summarisation task.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: calandriello24a
month: 0
tex_title: Human Alignment of Large Language Models through Online Preference Optimisation
firstpage: 5409
lastpage: 5435
page: 5409-5435
order: 5409
cycles: false
bibtex_author: Calandriello, Daniele and Guo, Zhaohan Daniel and Munos, Remi and Rowland,
  Mark and Tang, Yunhao and Avila Pires, Bernardo and Richemond, Pierre Harvey and
  Le Lan, Charline and Valko, Michal and Liu, Tianqi and Joshi, Rishabh and Zheng,
  Zeyu and Piot, Bilal
author:
- given: Daniele
  family: Calandriello
- given: Zhaohan Daniel
  family: Guo
- given: Remi
  family: Munos
- given: Mark
  family: Rowland
- given: Yunhao
  family: Tang
- given: Bernardo
  family: Avila Pires
- given: Pierre Harvey
  family: Richemond
- given: Charline
  family: Le Lan
- given: Michal
  family: Valko
- given: Tianqi
  family: Liu
- given: Rishabh
  family: Joshi
- given: Zeyu
  family: Zheng
- given: Bilal
  family: Piot
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/calandriello24a/calandriello24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
