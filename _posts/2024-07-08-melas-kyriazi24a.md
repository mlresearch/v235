---
title: 'IM-3D: Iterative Multiview Diffusion and Reconstruction for High-Quality 3D
  Generation'
openreview: swTG6xju8O
abstract: Most text-to-3D generators build upon off-the-shelf text-to-image models
  trained on billions of images. They use variants of Score Distillation Sampling
  (SDS), which is slow, somewhat unstable, and prone to artifacts. A mitigation is
  to fine-tune the 2D generator to be multi-view aware, which can help distillation
  or can be combined with reconstruction networks to output 3D objects directly. In
  this paper, we further explore the design space of text-to-3D models. We significantly
  improve multi-view generation by considering video instead of image generators.
  Combined with a 3D reconstruction algorithm which, by using Gaussian splatting,
  can optimize a robust image-based loss, we directly produce high-quality 3D outputs
  from the generated views. Our new method, IM-3D, reduces the number of evaluations
  of the 2D generator network 10-100$\times$, resulting in a much more efficient pipeline,
  better quality, fewer geometric inconsistencies, and higher yield of usable 3D assets.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: melas-kyriazi24a
month: 0
tex_title: "{IM}-3{D}: Iterative Multiview Diffusion and Reconstruction for High-Quality
  3{D} Generation"
firstpage: 35310
lastpage: 35323
page: 35310-35323
order: 35310
cycles: false
bibtex_author: Melas-Kyriazi, Luke and Laina, Iro and Rupprecht, Christian and Neverova,
  Natalia and Vedaldi, Andrea and Gafni, Oran and Kokkinos, Filippos
author:
- given: Luke
  family: Melas-Kyriazi
- given: Iro
  family: Laina
- given: Christian
  family: Rupprecht
- given: Natalia
  family: Neverova
- given: Andrea
  family: Vedaldi
- given: Oran
  family: Gafni
- given: Filippos
  family: Kokkinos
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/melas-kyriazi24a/melas-kyriazi24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
