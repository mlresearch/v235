---
title: By Tying Embeddings You Are Assuming the Distributional Hypothesis
openreview: yyYMAprcAR
abstract: In this work, we analyze both theoretically and empirically the effect of
  tied input-output embeddings—a popular technique that reduces the model size while
  often improving training. Interestingly, we found that this technique is connected
  to Harris (1954)’s distributional hypothesis—often portrayed by the famous Firth
  (1957)’s quote “a word is characterized by the company it keeps”. Specifically,
  our findings indicate that words (or, more broadly, symbols) with similar semantics
  tend to be encoded in similar input embeddings, while words that appear in similar
  contexts are encoded in similar output embeddings (thus explaining the semantic
  space arising in input and output embedding of foundational language models). As
  a consequence of these findings, the tying of the input and output embeddings is
  encouraged only when the distributional hypothesis holds for the underlying data.
  These results also provide insight into the embeddings of foundation language models
  (which are known to be semantically organized). Further, we complement the theoretical
  findings with several experiments supporting the claims.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bertolotti24a
month: 0
tex_title: By Tying Embeddings You Are Assuming the Distributional Hypothesis
firstpage: 3584
lastpage: 3610
page: 3584-3610
order: 3584
cycles: false
bibtex_author: Bertolotti, Francesco and Cazzola, Walter
author:
- given: Francesco
  family: Bertolotti
- given: Walter
  family: Cazzola
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/bertolotti24a/bertolotti24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
