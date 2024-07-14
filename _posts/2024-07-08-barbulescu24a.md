---
title: 'To Each (Textual Sequence) Its Own: Improving Memorized-Data Unlearning in
  Large Language Models'
openreview: FWlNA3et6X
abstract: LLMs have been found to memorize training textual sequences and regurgitate
  verbatim said sequences during text generation time. This fact is known to be the
  cause of privacy and related (e.g., copyright) problems. Unlearning in LLMs then
  takes the form of devising new algorithms that will properly deal with these side-effects
  of memorized data, while not hurting the model’s utility. We offer a fresh perspective
  towards this goal, namely, that each textual sequence to be forgotten should be
  treated differently when being unlearned based on its degree of memorization within
  the LLM. We contribute a new metric for measuring unlearning quality, an adversarial
  attack showing that SOTA algorithms lacking this perspective fail for privacy, and
  two new unlearning methods based on Gradient Ascent and Task Arithmetic, respectively.
  A comprehensive performance evaluation across an extensive suite of NLP tasks then
  mapped the solution space, identifying the best solutions under different scales
  in model capacities and forget set sizes and quantified the gains of the new approaches.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: barbulescu24a
month: 0
tex_title: 'To Each ({T}extual Sequence) Its Own: Improving Memorized-Data Unlearning
  in Large Language Models'
firstpage: 3003
lastpage: 3023
page: 3003-3023
order: 3003
cycles: false
bibtex_author: B\u{a}rbulescu, George-Octavian and Triantafillou, Peter
author:
- given: George-Octavian
  family: Bărbulescu
- given: Peter
  family: Triantafillou
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
pdf: https://proceedings.mlr.press/v235/assets/barbulescu24a/barbulescu24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
