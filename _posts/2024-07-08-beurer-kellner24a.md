---
title: 'Guiding LLMs The Right Way: Fast, Non-Invasive Constrained Generation'
openreview: pXaEYzrFae
abstract: To ensure that text generated by large language models (LLMs) is in an expected
  format, constrained decoding methods propose to enforce strict formal language constraints
  during generation. However, as we show in this work, not only do such methods often
  incur performance overhead during generation, but many of them also significantly
  impair task accuracy, if they do not correctly align the underlying LLM sub-word
  vocabularies with external constraints. To address this, we present a novel decoding
  algorithm, DOMINO, that can enforce constraints in a fully subword-aligned fashion,
  while leveraging pre-computation and speculative decoding to achieve virtually no
  overhead and in some cases even almost 2$\times$ speedup over unconstrained decoding
  – thereby outperforming existing approaches by a wide margin. We release DOMINO
  as open source at https://github.com/eth-sri/domino.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: beurer-kellner24a
month: 0
tex_title: 'Guiding {LLM}s The Right Way: Fast, Non-Invasive Constrained Generation'
firstpage: 3658
lastpage: 3673
page: 3658-3673
order: 3658
cycles: false
bibtex_author: Beurer-Kellner, Luca and Fischer, Marc and Vechev, Martin
author:
- given: Luca
  family: Beurer-Kellner
- given: Marc
  family: Fischer
- given: Martin
  family: Vechev
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/beurer-kellner24a/beurer-kellner24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
