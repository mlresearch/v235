---
title: Multi-Agent Reinforcement Learning with Hierarchical Coordination for Emergency
  Responder Stationing
openreview: TTZXl9WYFF
abstract: 'An emergency responder management (ERM) system dispatches responders, such
  as ambulances, when it receives requests for medical aid. ERM systems can also proactively
  reposition responders between predesignated waiting locations to cover any gaps
  that arise due to the prior dispatch of responders or significant changes in the
  distribution of anticipated requests. Optimal repositioning is computationally challenging
  due to the exponential number of ways to allocate responders between locations and
  the uncertainty in future requests. The state-of-the-art approach in proactive repositioning
  is a hierarchical approach based on spatial decomposition and online Monte Carlo
  tree search, which may require minutes of computation for each decision in a domain
  where seconds can save lives. We address the issue of long decision times by introducing
  a novel reinforcement learning (RL) approach, based on the same hierarchical decomposition,
  but replacing online search with learning. To address the computational challenges
  posed by large, variable-dimensional, and discrete state and action spaces, we propose:
  (1) actor-critic based agents that incorporate transformers to handle variable-dimensional
  states and actions, (2) projections to fixed-dimensional observations to handle
  complex states, and (3) combinatorial techniques to map continuous actions to discrete
  allocations. We evaluate our approach using real-world data from two U.S. cities,
  Nashville, TN and Seattle, WA. Our experiments show that compared to the state of
  the art, our approach reduces computation time per decision by three orders of magnitude,
  while also slightly reducing average ambulance response time by 5 seconds.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sivagnanam24a
month: 0
tex_title: Multi-Agent Reinforcement Learning with Hierarchical Coordination for Emergency
  Responder Stationing
firstpage: 45813
lastpage: 45834
page: 45813-45834
order: 45813
cycles: false
bibtex_author: Sivagnanam, Amutheezan and Pettet, Ava and Lee, Hunter and Mukhopadhyay,
  Ayan and Dubey, Abhishek and Laszka, Aron
author:
- given: Amutheezan
  family: Sivagnanam
- given: Ava
  family: Pettet
- given: Hunter
  family: Lee
- given: Ayan
  family: Mukhopadhyay
- given: Abhishek
  family: Dubey
- given: Aron
  family: Laszka
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
pdf: https://proceedings.mlr.press/v235/assets/sivagnanam24a/sivagnanam24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
