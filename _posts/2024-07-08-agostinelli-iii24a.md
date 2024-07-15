---
title: 'LeaPformer: Enabling Linear Transformers for Autoregressive and Simultaneous
  Tasks via Learned Proportions'
openreview: XhH1OKLANY
abstract: A promising approach to preserving model performance in linearized transformers
  is to employ position-based re-weighting functions. However, state-of-the-art re-weighting
  functions rely heavily on target sequence lengths, making it difficult or impossible
  to apply them to autoregressive and simultaneous tasks, where the target and sometimes
  even the input sequence length are unknown. To address this issue, we propose Learned
  Proportions (LeaP) and LeaPformers. Our contribution is built on two major components.
  First, we generalize the dependence on explicit positional representations and sequence
  lengths into dependence on sequence proportions for re-weighting. Second, we replace
  static positional representations with dynamic proportions derived via a compact
  module, enabling more flexible attention concentration patterns. We evaluate LeaPformer
  against eight representative efficient transformers on the Long-Range Arena benchmark,
  where we show that LeaPformer achieves the best quality-throughput trade-off, as
  well as apply LeaPformer to Wikitext-103b autoregressive language modeling and simultaneous
  speech-to-text translation for two language pairs, achieving competitive results
  in both tasks.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: agostinelli-iii24a
month: 0
tex_title: "{L}ea{P}former: Enabling Linear Transformers for Autoregressive and Simultaneous
  Tasks via Learned Proportions"
firstpage: 452
lastpage: 470
page: 452-470
order: 452
cycles: false
bibtex_author: Agostinelli Iii, Victor and Hong, Sanghyun and Chen, Lizhong
author:
- given: Victor
  family: Agostinelli Iii
- given: Sanghyun
  family: Hong
- given: Lizhong
  family: Chen
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/agostinelli-iii24a/agostinelli-iii24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
