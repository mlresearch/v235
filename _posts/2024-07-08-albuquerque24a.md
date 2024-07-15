---
title: Evaluating Model Bias Requires Characterizing its Mistakes
openreview: idyUNsoZ75
abstract: 'The ability to properly benchmark model performance in the face of spurious
  correlations is important to both build better predictors and increase confidence
  that models are operating as intended. We demonstrate that characterizing (as opposed
  to simply quantifying) model mistakes across subgroups is pivotal to properly reflect
  model biases, which are ignored by standard metrics such as worst-group accuracy
  or accuracy gap. Inspired by the hypothesis testing framework, we introduce SkewSize,
  a principled and flexible metric that captures bias from mistakes in a model’s predictions.
  It can be used in multi-class settings or generalised to the open vocabulary setting
  of generative models. SkewSize is an aggregation of the effect size of the interaction
  between two categorical variables: the spurious variable representing the bias attribute
  the model’s prediction. We demonstrate the utility of SkewSize in multiple settings
  including: standard vision models trained on synthetic data, vision models trained
  on ImageNet, and large scale vision-and-language models from the BLIP-2 family.
  In each case, the proposed SkewSize is able to highlight biases not captured by
  other metrics, while also providing insights on the impact of recently proposed
  techniques, such as instruction tuning.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: albuquerque24a
month: 0
tex_title: Evaluating Model Bias Requires Characterizing its Mistakes
firstpage: 938
lastpage: 954
page: 938-954
order: 938
cycles: false
bibtex_author: Albuquerque, Isabela and Schrouff, Jessica and Warde-Farley, David
  and Cemgil, Ali Taylan and Gowal, Sven and Wiles, Olivia
author:
- given: Isabela
  family: Albuquerque
- given: Jessica
  family: Schrouff
- given: David
  family: Warde-Farley
- given: Ali Taylan
  family: Cemgil
- given: Sven
  family: Gowal
- given: Olivia
  family: Wiles
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/albuquerque24a/albuquerque24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
