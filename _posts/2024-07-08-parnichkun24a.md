---
title: 'State-Free Inference of State-Space Models: The *Transfer Function* Approach'
openreview: DwwI9L67B5
abstract: 'We approach designing a state-space model for deep learning applications
  through its dual representation, the <em>transfer function</em>, and uncover a highly
  efficient sequence parallel inference algorithm that is <em>state-free</em>: unlike
  other proposed algorithms, state-free inference does not incur any significant memory
  or computational cost with an increase in state size. We achieve this using properties
  of the proposed frequency domain transfer function parametrization, which enables
  direct computation of its corresponding convolutional kernel’s spectrum via a single
  Fast Fourier Transform. Our experimental results across multiple sequence lengths
  and state sizes illustrates, on average, a 35% training speed improvement over S4
  layers – parametrized in time-domain – on the Long Range Arena benchmark, while
  delivering state-of-the-art downstream performances over other attention-free approaches.
  Moreover, we report improved perplexity in language modeling over a long convolutional
  Hyena baseline, by simply introducing our transfer function parametrization. Our
  code is available at https://github.com/ruke1ire/RTF.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: parnichkun24a
month: 0
tex_title: 'State-Free Inference of State-Space Models: The *{T}ransfer Function*
  Approach'
firstpage: 39834
lastpage: 39860
page: 39834-39860
order: 39834
cycles: false
bibtex_author: Parnichkun, Rom and Massaroli, Stefano and Moro, Alessandro and Smith,
  Jimmy T.H. and Hasani, Ramin and Lechner, Mathias and An, Qi and Re, Christopher
  and Asama, Hajime and Ermon, Stefano and Suzuki, Taiji and Poli, Michael and Yamashita,
  Atsushi
author:
- given: Rom
  family: Parnichkun
- given: Stefano
  family: Massaroli
- given: Alessandro
  family: Moro
- given: Jimmy T.H.
  family: Smith
- given: Ramin
  family: Hasani
- given: Mathias
  family: Lechner
- given: Qi
  family: An
- given: Christopher
  family: Re
- given: Hajime
  family: Asama
- given: Stefano
  family: Ermon
- given: Taiji
  family: Suzuki
- given: Michael
  family: Poli
- given: Atsushi
  family: Yamashita
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
pdf: https://proceedings.mlr.press/v235/parnichkun24a/parnichkun24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
