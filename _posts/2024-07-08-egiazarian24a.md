---
title: Extreme Compression of Large Language Models via Additive Quantization
openreview: 5mCaITRTmO
abstract: 'The emergence of accurate open large language models (LLMs) has led to
  a race towards performant quantization techniques which can enable their execution
  on end-user devices. In this paper, we revisit the problem of “extreme” LLM compression—defined
  as targeting extremely low bit counts, such as 2 to 3 bits per parameter—from the
  point of view of classic methods in Multi-Codebook Quantization (MCQ). Our algorithm,
  called AQLM, generalizes the classic <em>Additive Quantization (AQ)</em> approach
  for information retrieval to advance the state-of-the-art in LLM compression, via
  two innovations: 1) learned additive quantization of weight matrices in input-adaptive
  fashion, and 2) joint optimization of codebook parameters across each transformer
  blocks. Broadly, AQLM is the first scheme that is Pareto optimal in terms of accuracy-vs-model-size
  when compressing to less than 3 bits per parameter, and significantly improves upon
  all known schemes in the extreme compression (2bit) regime. In addition, AQLM is
  practical: we provide fast GPU and CPU implementations of AQLM for token generation,
  which enable us to match or outperform optimized FP16 implementations for speed,
  while executing in a much smaller memory footprint.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: egiazarian24a
month: 0
tex_title: Extreme Compression of Large Language Models via Additive Quantization
firstpage: 12284
lastpage: 12303
page: 12284-12303
order: 12284
cycles: false
bibtex_author: Egiazarian, Vage and Panferov, Andrei and Kuznedelev, Denis and Frantar,
  Elias and Babenko, Artem and Alistarh, Dan
author:
- given: Vage
  family: Egiazarian
- given: Andrei
  family: Panferov
- given: Denis
  family: Kuznedelev
- given: Elias
  family: Frantar
- given: Artem
  family: Babenko
- given: Dan
  family: Alistarh
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
pdf: https://proceedings.mlr.press/v235/egiazarian24a/egiazarian24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
