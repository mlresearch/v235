---
title: Multiply Robust Estimation for Local Distribution Shifts with Multiple Domains
openreview: hJaWoU3Emh
abstract: Distribution shifts are ubiquitous in real-world machine learning applications,
  posing a challenge to the generalization of models trained on one data distribution
  to another. We focus on scenarios where data distributions vary across multiple
  segments of the entire population and only make local assumptions about the differences
  between training and test (deployment) distributions within each segment. We propose
  a two-stage multiply robust estimation method to improve model performance on each
  individual segment for tabular data analysis. The method involves fitting a linear
  combination of the based models, learned using clusters of training data from multiple
  segments, followed by a refinement step for each segment. Our method is designed
  to be implemented with commonly used off-the-shelf machine learning models. We establish
  theoretical guarantees on the generalization bound of the method on the test risk.
  With extensive experiments on synthetic and real datasets, we demonstrate that the
  proposed method substantially improves over existing alternatives in prediction
  accuracy and robustness on both regression and classification tasks. We also assess
  its effectiveness on a user city prediction dataset from Meta.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: wilkins-reeves24a
month: 0
tex_title: Multiply Robust Estimation for Local Distribution Shifts with Multiple
  Domains
firstpage: 52972
lastpage: 52993
page: 52972-52993
order: 52972
cycles: false
bibtex_author: Wilkins-Reeves, Steven and Chen, Xu and Ma, Qi and Agarwal, Christine
  and Hofleitner, Aude
author:
- given: Steven
  family: Wilkins-Reeves
- given: Xu
  family: Chen
- given: Qi
  family: Ma
- given: Christine
  family: Agarwal
- given: Aude
  family: Hofleitner
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/wilkins-reeves24a/wilkins-reeves24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
