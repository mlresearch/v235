---
title: 'Prodigy: An Expeditiously Adaptive Parameter-Free Learner'
openreview: JJpOssn0uP
abstract: We consider the problem of estimating the learning rate in adaptive methods,
  such as AdaGrad and Adam. We propose Prodigy, an algorithm that provably estimates
  the distance to the solution $D$, which is needed to set the learning rate optimally.
  At its core, Prodigy is a modification of the D-Adaptation method for learning-rate-free
  learning. It improves upon the convergence rate of D-Adaptation by a factor of $\mathcal{O}(\sqrt{\log(D/d_0)})$,
  where $d_0$ is the initial estimate of $D$. We test Prodigy on 12 common logistic-regression
  benchmark datasets, VGG11 and ResNet-50 training on CIFAR10, ViT training on Imagenet,
  LSTM training on IWSLT14, DLRM training on Criteo dataset, VarNet on Knee MRI dataset,
  as well as RoBERTa and GPT transformer training on BookWiki. Our experimental results
  show that our approach consistently outperforms D-Adaptation and reaches test accuracy
  values close to that of hand-tuned Adam.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mishchenko24a
month: 0
tex_title: 'Prodigy: An Expeditiously Adaptive Parameter-Free Learner'
firstpage: 35779
lastpage: 35804
page: 35779-35804
order: 35779
cycles: false
bibtex_author: Mishchenko, Konstantin and Defazio, Aaron
author:
- given: Konstantin
  family: Mishchenko
- given: Aaron
  family: Defazio
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
pdf: https://proceedings.mlr.press/v235/assets/mishchenko24a/mishchenko24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
