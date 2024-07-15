---
title: Iterated Denoising Energy Matching for Sampling from Boltzmann Densities
openreview: gVjMwLDFoQ
abstract: Efficiently generating statistically independent samples from an unnormalized
  probability distribution, such as equilibrium samples of many-body systems, is a
  foundational problem in science. In this paper, we propose Iterated Denoising Energy
  Matching (iDEM), an iterative algorithm that uses a novel stochastic score matching
  objective leveraging solely the energy function and its gradient—and no data samples—to
  train a diffusion-based sampler. Specifically, iDEM alternates between (I) sampling
  regions of high model density from a diffusion-based sampler and (II) using these
  samples in our stochastic matching objective to further improve the sampler. iDEM
  is scalable to high dimensions as the inner matching objective, is <em>simulation-free</em>,
  and requires no MCMC samples. Moreover, by leveraging the fast mode mixing behavior
  of diffusion, iDEM smooths out the energy landscape enabling efficient exploration
  and learning of an amortized sampler. We evaluate iDEM on a suite of tasks ranging
  from standard synthetic energy functions to invariant $n$-body particle systems.
  We show that the proposed approach achieves state-of-the-art performance on all
  metrics and trains $2-5\times$ faster, which allows it to be the first method to
  train using energy on the challenging $55$-particle Lennard-Jones system.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: akhound-sadegh24a
month: 0
tex_title: Iterated Denoising Energy Matching for Sampling from Boltzmann Densities
firstpage: 760
lastpage: 786
page: 760-786
order: 760
cycles: false
bibtex_author: Akhound-Sadegh, Tara and Rector-Brooks, Jarrid and Bose, Joey and Mittal,
  Sarthak and Lemos, Pablo and Liu, Cheng-Hao and Sendera, Marcin and Ravanbakhsh,
  Siamak and Gidel, Gauthier and Bengio, Yoshua and Malkin, Nikolay and Tong, Alexander
author:
- given: Tara
  family: Akhound-Sadegh
- given: Jarrid
  family: Rector-Brooks
- given: Joey
  family: Bose
- given: Sarthak
  family: Mittal
- given: Pablo
  family: Lemos
- given: Cheng-Hao
  family: Liu
- given: Marcin
  family: Sendera
- given: Siamak
  family: Ravanbakhsh
- given: Gauthier
  family: Gidel
- given: Yoshua
  family: Bengio
- given: Nikolay
  family: Malkin
- given: Alexander
  family: Tong
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/akhound-sadegh24a/akhound-sadegh24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
