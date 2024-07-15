---
title: 'AI Control: Improving Safety Despite Intentional Subversion'
openreview: KviM5k8pcP
abstract: As large language models (LLMs) become more powerful and are deployed more
  autonomously, it will be increasingly important to prevent them from causing harmful
  outcomes. To do so, safety measures either aim at making LLMs try to avoid harmful
  outcomes or aim at preventing LLMs from causing harmful outcomes, even if they try
  to cause them. In this paper, we focus on this second layer of defense. We develop
  and evaluate pipelines of safety techniques (protocols) that try to ensure safety
  despite intentional subversion - an approach we call AI control. We investigate
  a setting in which we want to solve a sequence of programming problems without ever
  submitting subtly wrong code, using access to a powerful but untrusted model (in
  our case, GPT-4), access to a less powerful trusted model (in our case, GPT-3.5),
  and limited access to high-quality trusted labor. We investigate a range of protocols
  and red-team them by exploring strategies that the untrusted model could use to
  subvert them. We find that using the trusted model to edit untrusted-model code
  or using the untrusted model as a monitor substantially improves on simple baselines.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: greenblatt24a
month: 0
tex_title: "{AI} Control: Improving Safety Despite Intentional Subversion"
firstpage: 16295
lastpage: 16336
page: 16295-16336
order: 16295
cycles: false
bibtex_author: Greenblatt, Ryan and Shlegeris, Buck and Sachan, Kshitij and Roger,
  Fabien
author:
- given: Ryan
  family: Greenblatt
- given: Buck
  family: Shlegeris
- given: Kshitij
  family: Sachan
- given: Fabien
  family: Roger
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/greenblatt24a/greenblatt24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
