---
title: Bifurcated Attention for Single-Context Large-Batch Sampling
openreview: JPNBFWQ9H2
abstract: In our study, we present bifurcated attention, a method developed for language
  model inference in single-context batch sampling contexts. This approach aims to
  reduce redundant memory IO costs, a significant factor in latency for high batch
  sizes and long context lengths. Bifurcated attention achieves this by dividing the
  attention mechanism during incremental decoding into two distinct GEMM operations,
  focusing on the KV cache from prefill and the decoding process. This method ensures
  precise computation and maintains the usual computational load (FLOPs) of standard
  attention mechanisms, but with reduced memory IO. Bifurcated attention is also compatible
  with multi-query attention mechanism known for reduced memory IO for KV cache, further
  enabling higher batch size and context length. The resulting efficiency leads to
  lower latency, improving suitability for real-time applications, e.g., enabling
  massively-parallel answer generation without substantially increasing latency, enhancing
  performance when integrated with post-processing techniques such as reranking.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: athiwaratkun24a
month: 0
tex_title: Bifurcated Attention for Single-Context Large-Batch Sampling
firstpage: 1971
lastpage: 1991
page: 1971-1991
order: 1971
cycles: false
bibtex_author: Athiwaratkun, Ben and Gonugondla, Sujan Kumar and Gouda, Sanjay Krishna
  and Qian, Haifeng and Ding, Hantian and Sun, Qing and Wang, Jun and Guo, Jiacheng
  and Chen, Liangfu and Bhatia, Parminder and Nallapati, Ramesh and Sengupta, Sudipta
  and Xiang, Bing
author:
- given: Ben
  family: Athiwaratkun
- given: Sujan Kumar
  family: Gonugondla
- given: Sanjay Krishna
  family: Gouda
- given: Haifeng
  family: Qian
- given: Hantian
  family: Ding
- given: Qing
  family: Sun
- given: Jun
  family: Wang
- given: Jiacheng
  family: Guo
- given: Liangfu
  family: Chen
- given: Parminder
  family: Bhatia
- given: Ramesh
  family: Nallapati
- given: Sudipta
  family: Sengupta
- given: Bing
  family: Xiang
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/athiwaratkun24a/athiwaratkun24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
