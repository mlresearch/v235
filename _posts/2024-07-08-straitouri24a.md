---
title: Designing Decision Support Systems using Counterfactual Prediction Sets
openreview: rqyXubsBhH
abstract: Decision support systems for classification tasks are predominantly designed
  to predict the value of the ground truth labels. However, since their predictions
  are not perfect, these systems also need to make human experts understand when and
  how to use these predictions to update their own predictions. Unfortunately, this
  has been proven challenging. In this context, it has been recently argued that an
  alternative type of decision support systems may circumvent this challenge. Rather
  than providing a single label prediction, these systems provide a set of label prediction
  values constructed using a conformal predictor, namely a prediction set, and forcefully
  ask experts to predict a label value from the prediction set. However, the design
  and evaluation of these systems have so far relied on stylized expert models, questioning
  their promise. In this paper, we revisit the design of this type of systems from
  the perspective of online learning and develop a methodology that does not require,
  nor assumes, an expert model. Our methodology leverages the nested structure of
  the prediction sets provided by any conformal predictor and a natural counterfactual
  monotonicity assumption to achieve an exponential improvement in regret in comparison
  to vanilla bandit algorithms. We conduct a large-scale human subject study ($n =
  2{,}751$) to compare our methodology to several competitive baselines. The results
  show that, for decision support systems based on prediction sets, limiting experts’
  level of agency leads to greater performance than allowing experts to always exercise
  their own agency.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: straitouri24a
month: 0
tex_title: Designing Decision Support Systems using Counterfactual Prediction Sets
firstpage: 46722
lastpage: 46744
page: 46722-46744
order: 46722
cycles: false
bibtex_author: Straitouri, Eleni and Gomez Rodriguez, Manuel
author:
- given: Eleni
  family: Straitouri
- given: Manuel
  family: Gomez Rodriguez
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
pdf: https://proceedings.mlr.press/v235/straitouri24a/straitouri24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
