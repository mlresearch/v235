---
title: Neural Operators with Localized Integral and Differential Kernels
openreview: vl9GB3fbht
abstract: Neural operators learn mappings between function spaces, which is practical
  for learning solution operators of PDEs and other scientific modeling applications.
  Among them, the Fourier neural operator (FNO) is a popular architecture that performs
  global convolutions in the Fourier space. However, such global operations are often
  prone to over-smoothing and may fail to capture local details. In contrast, convolutional
  neural networks (CNN) can capture local features but are limited to training and
  inference at a single resolution. In this work, we present a principled approach
  to operator learning that can capture local features under two frameworks by learning
  differential operators and integral operators with locally supported kernels. Specifically,
  inspired by stencil methods, we prove that we obtain differential operators under
  an appropriate scaling of the kernel values of CNNs. To obtain local integral operators,
  we utilize suitable basis representations for the kernels based on discrete-continuous
  convolutions. Both these approaches preserve the properties of operator learning
  and, hence, the ability to predict at any resolution. Adding our layers to FNOs
  significantly improves their performance, reducing the relative L2-error by 34-72%
  in our experiments, which include a turbulent 2D Navier-Stokes and the spherical
  shallow water equations.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: liu-schiaffini24a
month: 0
tex_title: Neural Operators with Localized Integral and Differential Kernels
firstpage: 32576
lastpage: 32594
page: 32576-32594
order: 32576
cycles: false
bibtex_author: Liu-Schiaffini, Miguel and Berner, Julius and Bonev, Boris and Kurth,
  Thorsten and Azizzadenesheli, Kamyar and Anandkumar, Anima
author:
- given: Miguel
  family: Liu-Schiaffini
- given: Julius
  family: Berner
- given: Boris
  family: Bonev
- given: Thorsten
  family: Kurth
- given: Kamyar
  family: Azizzadenesheli
- given: Anima
  family: Anandkumar
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/liu-schiaffini24a/liu-schiaffini24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
