---
title: Benchmarking and Building Long-Context Retrieval Models with LoCo and M2-BERT
openreview: HkCRgoGtt6
abstract: 'Retrieval pipelines are an integral component of many machine learning
  systems. However, they perform poorly in domains where documents are long (e.g.,
  10K tokens or more) and where identifying the relevant document requires synthesizing
  information across the entire text. Developing long-context retrieval encoders suitable
  for these domains raises three challenges: (1) how to evaluate long-context retrieval
  performance, (2) how to pretrain a base language model to represent both short contexts
  (corresponding to queries) and long contexts (corresponding to documents), and (3)
  how to finetune this model for retrieval under the batch size limitations imposed
  by GPU memory constraints. To address these challenges, we first introduce LoCoV1,
  a 12 task benchmark constructed to measure long-context retrieval where chunking
  is not possible or not effective. We next present the M2-BERT retrieval encoder,
  an 80M parameter state-space encoder model built from the Monarch Mixer architecture,
  capable of scaling to documents up to 32K tokens long. We describe a pretraining
  data mixture which allows this encoder to process both short and long context sequences,
  and a finetuning approach that adapts this base model to retrieval with only single-sample
  batches. Finally, we validate the M2-BERT retrieval encoder on LoCoV1, finding that
  it outperforms competitive Transformer-based models by at least 22.2 points, despite
  containing 90× fewer parameters.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: saad-falcon24a
month: 0
tex_title: Benchmarking and Building Long-Context Retrieval Models with {L}o{C}o and
  M2-{BERT}
firstpage: 42918
lastpage: 42946
page: 42918-42946
order: 42918
cycles: false
bibtex_author: Saad-Falcon, Jon and Fu, Daniel Y and Arora, Simran and Guha, Neel
  and Re, Christopher
author:
- given: Jon
  family: Saad-Falcon
- given: Daniel Y
  family: Fu
- given: Simran
  family: Arora
- given: Neel
  family: Guha
- given: Christopher
  family: Re
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
pdf: https://proceedings.mlr.press/v235/assets/saad-falcon24a/saad-falcon24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
