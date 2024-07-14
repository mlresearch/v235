---
title: 'ReGAL: Refactoring Programs to Discover Generalizable Abstractions'
openreview: FovMAzXUpj
abstract: While large language models (LLMs) are increasingly being used for program
  synthesis, they lack the global view needed to develop useful abstractions; they
  generally predict programs one at a time, often repeating the same functionality.
  Generating redundant code from scratch is both inefficient and error-prone. To address
  this, we propose Refactoring for Generalizable Abstraction Learning (ReGAL), a gradient-free
  method for learning a library of reusable functions via code refactorization, i.e.,
  restructuring code without changing its execution output. ReGAL learns from a small
  set of existing programs, iteratively verifying and refining its abstractions via
  execution. We find that the shared function libraries discovered by ReGAL make programs
  easier to predict across diverse domains. On five datasets – LOGO graphics generation,
  Date reasoning, TextCraft (a Minecraft-based text-game) MATH, and TabMWP – both
  open-source and proprietary LLMs improve in accuracy when predicting programs with
  REGAL functions. For CodeLlama-13B, REGAL results in absolute accuracy increases
  of 11.5% on LOGO, 26.1% on date understanding, and 8.1% on TextCraft, out-performing
  GPT-3.5 in two of three domains. Our analysis reveals REGAL’s abstractions encapsulate
  frequently-used subroutines as well as environment dynamics.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: stengel-eskin24a
month: 0
tex_title: "{R}e{GAL}: Refactoring Programs to Discover Generalizable Abstractions"
firstpage: 46605
lastpage: 46624
page: 46605-46624
order: 46605
cycles: false
bibtex_author: Stengel-Eskin, Elias and Prasad, Archiki and Bansal, Mohit
author:
- given: Elias
  family: Stengel-Eskin
- given: Archiki
  family: Prasad
- given: Mohit
  family: Bansal
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
pdf: https://proceedings.mlr.press/v235/assets/stengel-eskin24a/stengel-eskin24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
