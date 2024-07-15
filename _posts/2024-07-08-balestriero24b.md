---
title: How Learning by Reconstruction Produces Uninformative Features For Perception
openreview: XsDWw1Mn2p
abstract: Input space reconstruction is an attractive representation learning paradigm.
  Despite interpretability benefit of reconstruction and generation, we identify a
  misalignment between learning to reconstruct, and learning for perception. We show
  that the former allocates a model’s capacity towards a subspace of the data explaining
  the observed variance–a subspace with uninformative features for the latter. For
  example, the supervised TinyImagenet task with images projected onto the top subspace
  explaining 90% of the pixel variance can be solved with 45% test accuracy. Using
  the bottom subspace instead, accounting for only 20% of the pixel variance, reaches
  55% test accuracy. Learning by reconstruction is also wasteful as the features for
  perception are learned last, pushing the need for long training schedules. We finally
  prove that learning by denoising can alleviate that misalignment for some noise
  strategies, e.g., masking. While tuning the noise strategy without knowledge of
  the perception task seems challenging, we provide a solution to detect if a noise
  strategy is never beneficial regardless of the perception task, e.g., additive Gaussian
  noise.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: balestriero24b
month: 0
tex_title: How Learning by Reconstruction Produces Uninformative Features For Perception
firstpage: 2566
lastpage: 2585
page: 2566-2585
order: 2566
cycles: false
bibtex_author: Balestriero, Randall and Lecun, Yann
author:
- given: Randall
  family: Balestriero
- given: Yann
  family: Lecun
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/balestriero24b/balestriero24b.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
