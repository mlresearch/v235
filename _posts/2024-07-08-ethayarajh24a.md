---
title: Model Alignment as Prospect Theoretic Optimization
openreview: iUwHnoENnl
abstract: Kahneman & Tversky’s $\textit{prospect theory}$ tells us that humans perceive
  random variables in a biased but well-defined manner (1992); for example, humans
  are famously loss-averse. We show that objectives for aligning LLMs with human feedback
  implicitly incorporate many of these biases—the success of these objectives (e.g.,
  DPO) over cross-entropy minimization can partly be ascribed to them belonging to
  a family of loss functions that we call $\textit{human-aware losses}$ (HALOs). However,
  the utility functions these methods attribute to humans still differ from those
  in the prospect theory literature. Using a Kahneman-Tversky model of human utility,
  we propose a HALO that directly maximizes the utility of generations instead of
  maximizing the log-likelihood of preferences, as current methods do. We call this
  approach KTO, and it matches or exceeds the performance of preference-based methods
  at scales from 1B to 30B, despite only learning from a binary signal of whether
  an output is desirable. More broadly, our work suggests that there is no one HALO
  that is universally superior; the best loss depends on the inductive biases most
  appropriate for a given setting, an oft-overlooked consideration.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ethayarajh24a
month: 0
tex_title: Model Alignment as Prospect Theoretic Optimization
firstpage: 12634
lastpage: 12651
page: 12634-12651
order: 12634
cycles: false
bibtex_author: Ethayarajh, Kawin and Xu, Winnie and Muennighoff, Niklas and Jurafsky,
  Dan and Kiela, Douwe
author:
- given: Kawin
  family: Ethayarajh
- given: Winnie
  family: Xu
- given: Niklas
  family: Muennighoff
- given: Dan
  family: Jurafsky
- given: Douwe
  family: Kiela
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
pdf: https://proceedings.mlr.press/v235/assets/ethayarajh24a/ethayarajh24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
