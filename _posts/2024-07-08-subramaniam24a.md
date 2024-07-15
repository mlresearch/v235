---
title: Revealing Vision-Language Integration in the Brain with Multimodal Networks
openreview: pD9BTIDUoX
abstract: We use (multi)modal deep neural networks (DNNs) to probe for sites of multimodal
  integration in the human brain by predicting stereoencephalography (SEEG) recordings
  taken while human subjects watched movies. We operationalize sites of multimodal
  integration as regions where a multimodal vision-language model predicts recordings
  better than unimodal language, unimodal vision, or linearly-integrated language-vision
  models. Our target DNN models span different architectures (e.g., convolutional
  networks and transformers) and multimodal training techniques (e.g., cross-attention
  and contrastive learning). As a key enabling step, we first demonstrate that trained
  vision and language models systematically outperform their randomly initialized
  counterparts in their ability to predict SEEG signals. We then compare unimodal
  and multimodal models against one another. Because our target DNN models often have
  different architectures, number of parameters, and training sets (possibly obscuring
  those differences attributable to integration), we carry out a controlled comparison
  of two models (SLIP and SimCLR), which keep all of these attributes the same aside
  from input modality. Using this approach, we identify a sizable number of neural
  sites (on average 141 out of 1090 total sites or 12.94%) and brain regions where
  multimodal integration seems to occur. Additionally, we find that among the variants
  of multimodal training techniques we assess, CLIP-style training is the best suited
  for downstream prediction of the neural activity in these sites.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: subramaniam24a
month: 0
tex_title: Revealing Vision-Language Integration in the Brain with Multimodal Networks
firstpage: 46868
lastpage: 46890
page: 46868-46890
order: 46868
cycles: false
bibtex_author: Subramaniam, Vighnesh and Conwell, Colin and Wang, Christopher and
  Kreiman, Gabriel and Katz, Boris and Cases, Ignacio and Barbu, Andrei
author:
- given: Vighnesh
  family: Subramaniam
- given: Colin
  family: Conwell
- given: Christopher
  family: Wang
- given: Gabriel
  family: Kreiman
- given: Boris
  family: Katz
- given: Ignacio
  family: Cases
- given: Andrei
  family: Barbu
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/subramaniam24a/subramaniam24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
