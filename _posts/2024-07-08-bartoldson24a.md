---
title: Adversarial Robustness Limits via Scaling-Law and Human-Alignment Studies
openreview: HQtTg1try7
abstract: 'This paper revisits the simple, long-studied, yet still unsolved problem
  of making image classifiers robust to imperceptible perturbations. Taking CIFAR10
  as an example, SOTA clean accuracy is about $100$%, but SOTA robustness to $\ell_{\infty}$-norm
  bounded perturbations barely exceeds $70$%. To understand this gap, we analyze how
  model size, dataset size, and synthetic data quality affect robustness by developing
  the first scaling laws for adversarial training. Our scaling laws reveal inefficiencies
  in prior art and provide actionable feedback to advance the field. For instance,
  we discovered that SOTA methods diverge notably from compute-optimal setups, using
  excess compute for their level of robustness. Leveraging a compute-efficient setup,
  we surpass the prior SOTA with $20$% ($70$%) fewer training (inference) FLOPs. We
  trained various compute-efficient models, with our best achieving $74$% AutoAttack
  accuracy ($+3$% gain). However, our scaling laws also predict robustness slowly
  grows then plateaus at $90$%: dwarfing our new SOTA by scaling is impractical, and
  perfect robustness is impossible. To better understand this predicted limit, we
  carry out a small-scale human evaluation on the AutoAttack data that fools our top-performing
  model. Concerningly, we estimate that human performance also plateaus near $90$%,
  which we show to be attributable to $\ell_{\infty}$-constrained attacks’ generation
  of invalid images not consistent with their original labels. Having characterized
  limiting roadblocks, we outline promising paths for future research.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bartoldson24a
month: 0
tex_title: Adversarial Robustness Limits via Scaling-Law and Human-Alignment Studies
firstpage: 3046
lastpage: 3072
page: 3046-3072
order: 3046
cycles: false
bibtex_author: Bartoldson, Brian R. and Diffenderfer, James and Parasyris, Konstantinos
  and Kailkhura, Bhavya
author:
- given: Brian R.
  family: Bartoldson
- given: James
  family: Diffenderfer
- given: Konstantinos
  family: Parasyris
- given: Bhavya
  family: Kailkhura
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
pdf: https://proceedings.mlr.press/v235/assets/bartoldson24a/bartoldson24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
