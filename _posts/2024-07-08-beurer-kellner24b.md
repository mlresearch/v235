---
title: Prompt Sketching for Large Language Models
openreview: 2Yu5FWdzde
abstract: Many recent prompting strategies for large language models (LLMs) query
  the model multiple times sequentially – first to produce intermediate results and
  then the final answer. However, using these methods, both decoder and model are
  unaware of potential follow-up prompts, leading to disconnected and undesirably
  wordy intermediate responses. In this work, we address this issue by proposing prompt
  sketching, a new prompting paradigm in which an LLM does not only respond by completing
  a prompt, but by predicting values for multiple variables in a template. This way,
  sketching grants users more control over the generation process, e.g., by providing
  a reasoning framework via intermediate instructions, leading to better overall results.
  The key idea enabling sketching with existing, autoregressive models is to adapt
  the decoding procedure to also score follow-up instructions during text generation,
  thus optimizing overall template likelihood in inference. Our experiments show that
  in a zero-shot setting, prompt sketching outperforms existing, sequential prompting
  schemes such as direct asking or chain-of-thought on 7 out of 8 LLM benchmarking
  tasks, including state tracking, arithmetic reasoning, and general question answering.
  To facilitate future use, we release a number of generic, yet effective sketches
  applicable to many tasks, and an open source library called dclib, powering our
  sketch-aware decoders as part of https://github.com/eth-sri/lmql.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: beurer-kellner24b
month: 0
tex_title: Prompt Sketching for Large Language Models
firstpage: 3674
lastpage: 3706
page: 3674-3706
order: 3674
cycles: false
bibtex_author: Beurer-Kellner, Luca and Mueller, Mark Niklas and Fischer, Marc and
  Vechev, Martin
author:
- given: Luca
  family: Beurer-Kellner
- given: Mark Niklas
  family: Mueller
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
pdf: https://proceedings.mlr.press/v235/beurer-kellner24b/beurer-kellner24b.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
