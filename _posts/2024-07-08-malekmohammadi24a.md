---
title: Noise-Aware Algorithm for Heterogeneous Differentially Private Federated Learning
openreview: wuQ2DRPAuy
abstract: 'High utility and rigorous data privacy are of the main goals of a federated
  learning (FL) system, which learns a model from the data distributed among some
  clients. The latter has been tried to achieve by using differential privacy in FL
  (DPFL). There is often heterogeneity in clients’ privacy requirements, and existing
  DPFL works either assume uniform privacy requirements for clients or are not applicable
  when server is not fully trusted (our setting). Furthermore, there is often heterogeneity
  in batch and/or dataset size of clients, which as shown, results in extra variation
  in the DP noise level across clients’ model updates. With these sources of heterogeneity,
  straightforward aggregation strategies, e.g., assigning clients’ aggregation weights
  proportional to their privacy parameters ($\epsilon$) will lead to lower utility.
  We propose Robust-HDP, which efficiently estimates the true noise level in clients’
  model updates and reduces the noise-level in the aggregated model updates considerably.
  Robust-HDP improves utility and convergence speed, while being safe to the clients
  that may maliciously send falsified privacy parameter $\epsilon$ to server. Extensive
  experimental results on multiple datasets and our theoretical analysis confirm the
  effectiveness of Robust-HDP. Our code can be found here: https://github.com/Saber-mm/HDPFL.git'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: malekmohammadi24a
month: 0
tex_title: Noise-Aware Algorithm for Heterogeneous Differentially Private Federated
  Learning
firstpage: 34461
lastpage: 34498
page: 34461-34498
order: 34461
cycles: false
bibtex_author: Malekmohammadi, Saber and Yu, Yaoliang and Cao, Yang
author:
- given: Saber
  family: Malekmohammadi
- given: Yaoliang
  family: Yu
- given: Yang
  family: Cao
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/malekmohammadi24a/malekmohammadi24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
