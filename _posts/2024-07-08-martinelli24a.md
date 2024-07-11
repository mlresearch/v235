---
title: 'Expand-and-Cluster: Parameter Recovery of Neural Networks'
openreview: 3MIuPRJYwf
abstract: 'Can we identify the weights of a neural network by probing its input-output
  mapping? At first glance, this problem seems to have many solutions because of permutation,
  overparameterisation and activation function symmetries. Yet, we show that the incoming
  weight vector of each neuron is identifiable up to sign or scaling, depending on
  the activation function. Our novel method ’Expand-and-Cluster’ can identify layer
  sizes and weights of a target network for all commonly used activation functions.
  Expand-and-Cluster consists of two phases: (i) to relax the non-convex optimisation
  problem, we train multiple overparameterised student networks to best imitate the
  target function; (ii) to reverse engineer the target network’s weights, we employ
  an ad-hoc clustering procedure that reveals the learnt weight vectors shared between
  students – these correspond to the target weight vectors. We demonstrate successful
  weights and size recovery of trained shallow and deep networks with less than 10%
  overhead in the layer size and describe an ’ease-of-identifiability’ axis by analysing
  150 synthetic problems of variable difficulty.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: martinelli24a
month: 0
tex_title: 'Expand-and-Cluster: Parameter Recovery of Neural Networks'
firstpage: 34895
lastpage: 34919
page: 34895-34919
order: 34895
cycles: false
bibtex_author: Martinelli, Flavio and Simsek, Berfin and Gerstner, Wulfram and Brea,
  Johanni
author:
- given: Flavio
  family: Martinelli
- given: Berfin
  family: Simsek
- given: Wulfram
  family: Gerstner
- given: Johanni
  family: Brea
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
pdf: https://proceedings.mlr.press/v235/martinelli24a/martinelli24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
