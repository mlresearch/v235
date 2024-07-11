---
title: Challenges and Considerations in the Evaluation of Bayesian Causal Discovery
openreview: bqgtkBDkNs
abstract: 'Representing uncertainty in causal discovery is a crucial component for
  experimental design, and more broadly, for safe and reliable causal decision making.
  Bayesian Causal Discovery (BCD) offers a principled approach to encapsulating this
  uncertainty. Unlike non-Bayesian causal discovery, which relies on a single estimated
  causal graph and model parameters for assessment, evaluating BCD presents challenges
  due to the nature of its inferred quantity – the posterior distribution. As a result,
  the research community has proposed various metrics to assess the quality of the
  approximate posterior. However, there is, to date, no consensus on the most suitable
  metric(s) for evaluation. In this work, we reexamine this question by dissecting
  various metrics and understanding their limitations. Through extensive empirical
  evaluation, we find that many existing metrics fail to exhibit a strong correlation
  with the quality of approximation to the true posterior, especially in scenarios
  with low sample sizes where BCD is most desirable. We highlight the suitability
  (or lack thereof) of these metrics under two distinct factors: the identifiability
  of the underlying causal model and the quantity of available data. Both factors
  affect the entropy of the true posterior, indicating that the current metrics are
  less fitting in settings of higher entropy. Our findings underline the importance
  of a more nuanced evaluation of new methods by taking into account the nature of
  the true posterior, as well as guide and motivate the development of new evaluation
  procedures for this challenge.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: karimi-mamaghan24a
month: 0
tex_title: Challenges and Considerations in the Evaluation of {B}ayesian Causal Discovery
firstpage: 23215
lastpage: 23237
page: 23215-23237
order: 23215
cycles: false
bibtex_author: Karimi Mamaghan, Amir Mohammad and Tigas, Panagiotis and Johansson,
  Karl Henrik and Gal, Yarin and Annadani, Yashas and Bauer, Stefan
author:
- given: Amir Mohammad
  family: Karimi Mamaghan
- given: Panagiotis
  family: Tigas
- given: Karl Henrik
  family: Johansson
- given: Yarin
  family: Gal
- given: Yashas
  family: Annadani
- given: Stefan
  family: Bauer
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
pdf: https://proceedings.mlr.press/v235/karimi-mamaghan24a/karimi-mamaghan24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
