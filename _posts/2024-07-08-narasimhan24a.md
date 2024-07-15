---
title: 'Time Weaver: A Conditional Time Series Generation Model'
openreview: WpKDeixmFr
abstract: Imagine generating a city’s electricity demand pattern based on weather,
  the presence of an electric vehicle, and location, which could be used for capacity
  planning during a winter freeze. Such real-world time series are often enriched
  with paired heterogeneous contextual metadata (e.g., weather and location). Current
  approaches to time series generation often ignore this paired metadata. Additionally,
  the heterogeneity in metadata poses several practical challenges in adapting existing
  conditional generation approaches from the image, audio, and video domains to the
  time series domain. To address this gap, we introduce TIME WEAVER, a novel diffusion-based
  model that leverages the heterogeneous metadata in the form of categorical, continuous,
  and even time-variant variables to significantly improve time series generation.
  Additionally, we show that naive extensions of standard evaluation metrics from
  the image to the time series domain are insufficient. These metrics do not penalize
  conditional generation approaches for their poor specificity in reproducing the
  metadata-specific features in the generated time series. Thus, we innovate a novel
  evaluation metric that accurately captures the specificity of conditional generation
  and the realism of the generated time series. We show that TIME WEAVER outperforms
  state-of-the-art benchmarks, such as Generative Adversarial Networks (GANs), by
  up to 30% in downstream classification tasks on real-world energy, medical, air
  quality, and traffic datasets.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: narasimhan24a
month: 0
tex_title: 'Time Weaver: A Conditional Time Series Generation Model'
firstpage: 37293
lastpage: 37320
page: 37293-37320
order: 37293
cycles: false
bibtex_author: Narasimhan, Sai Shankar and Agarwal, Shubhankar and Akcin, Oguzhan
  and Sanghavi, Sujay and Chinchali, Sandeep P.
author:
- given: Sai Shankar
  family: Narasimhan
- given: Shubhankar
  family: Agarwal
- given: Oguzhan
  family: Akcin
- given: Sujay
  family: Sanghavi
- given: Sandeep P.
  family: Chinchali
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/narasimhan24a/narasimhan24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
