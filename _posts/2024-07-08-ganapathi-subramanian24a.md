---
title: Confidence Aware Inverse Constrained Reinforcement Learning
openreview: 6TCeizkLJV
abstract: In coming up with solutions to real-world problems, humans implicitly adhere
  to constraints that are too numerous and complex to be specified completely. However,
  reinforcement learning (RL) agents need these constraints to learn the correct optimal
  policy in these settings. The field of Inverse Constraint Reinforcement Learning
  (ICRL) deals with this problem and provides algorithms that aim to estimate the
  constraints from expert demonstrations collected offline. Practitioners prefer to
  know a measure of confidence in the estimated constraints, before deciding to use
  these constraints, which allows them to only use the constraints that satisfy a
  desired level of confidence. However, prior works do not allow users to provide
  the desired level of confidence for the inferred constraints. This work provides
  a principled ICRL method that can take a confidence level with a set of expert demonstrations
  and outputs a constraint that is at least as constraining as the true underlying
  constraint with the desired level of confidence. Further, unlike previous methods,
  this method allows a user to know if the number of expert trajectories is insufficient
  to learn a constraint with a desired level of confidence, and therefore collect
  more expert trajectories as required to simultaneously learn constraints with the
  desired level of confidence and a policy that achieves the desired level of performance.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ganapathi-subramanian24a
month: 0
tex_title: Confidence Aware Inverse Constrained Reinforcement Learning
firstpage: 14491
lastpage: 14512
page: 14491-14512
order: 14491
cycles: false
bibtex_author: Ganapathi Subramanian, Sriram and Liu, Guiliang and Elmahgiubi, Mohammed
  and Rezaee, Kasra and Poupart, Pascal
author:
- given: Sriram
  family: Ganapathi Subramanian
- given: Guiliang
  family: Liu
- given: Mohammed
  family: Elmahgiubi
- given: Kasra
  family: Rezaee
- given: Pascal
  family: Poupart
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/ganapathi-subramanian24a/ganapathi-subramanian24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
