---
title: 'Sparse-IFT: Sparse Iso-FLOP Transformations for Maximizing Training Efficiency'
openreview: X8Ha2NiQcy
abstract: 'Recent research has focused on weight sparsity in deep neural network training
  to reduce FLOPs, aiming for improved efficiency (test accuracy w.r.t training FLOPs).
  However, sparse weight training often compromises accuracy, requiring extended training
  schedules to attain the accuracy of dense models. In contrast, our approach, Sparse
  Iso-FLOP Transformations (Sparse-IFT), uses sparsity to improve accuracy while maintaining
  dense model FLOPs. Using a single hyperparameter (i.e., the sparsity level), Sparse-IFTs
  efficiently replace dense layers, expanding the search space for optimal sparse
  masks. In addition, dynamic sparse training (DST) with Sparse-IFT models effectively
  navigate this larger sparse mask-weight space, which is evidenced by a spectral
  analysis using Ramanujan graph properties. Our study reveals a robust correlation
  among mask topology, weights, and final performance. Notably, without adjusting
  any training hyperparameters, replacing dense layers with Sparse-IFT yields significant
  improvements, such as a +3.5% boost for ResNet-18 on ImageNet and +0.9% for GPT-3
  Small on the Open LLM leaderboard. To the best of our knowledge, this is the first
  work to demonstrate the use of sparsity for improving the accuracy of dense models
  through a set of simple-to-use sparse transformations. Code is available at: https://github.com/CerebrasResearch/Sparse-IFT.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: thangarasa24a
month: 0
tex_title: 'Sparse-{IFT}: Sparse Iso-{FLOP} Transformations for Maximizing Training
  Efficiency'
firstpage: 47997
lastpage: 48018
page: 47997-48018
order: 47997
cycles: false
bibtex_author: Thangarasa, Vithursan and Saxena, Shreyas and Gupta, Abhay and Lie,
  Sean
author:
- given: Vithursan
  family: Thangarasa
- given: Shreyas
  family: Saxena
- given: Abhay
  family: Gupta
- given: Sean
  family: Lie
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/thangarasa24a/thangarasa24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
