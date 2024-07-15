---
title: 'Listening to the noise: Blind Denoising with Gibbs Diffusion'
openreview: rmEgJ7bhuZ
abstract: In recent years, denoising problems have become intertwined with the development
  of deep generative models. In particular, diffusion models are trained like denoisers,
  and the distribution they model coincide with denoising priors in the Bayesian picture.
  However, denoising through diffusion-based posterior sampling requires the noise
  level and covariance to be known, preventing <em>blind denoising</em>. We overcome
  this limitation by introducing Gibbs Diffusion (GDiff), a general methodology addressing
  posterior sampling of both the signal and the noise parameters. Assuming arbitrary
  parametric Gaussian noise, we develop a Gibbs algorithm that alternates sampling
  steps from a conditional diffusion model trained to map the signal prior to the
  class of noise distributions, and a Monte Carlo sampler to infer the noise parameters.
  Our theoretical analysis highlights potential pitfalls, guides diagnostic usage,
  and quantifies errors in the Gibbs stationary distribution caused by the diffusion
  model. We showcase our method for 1) blind denoising of natural images involving
  colored noises with unknown amplitude and exponent, and 2) a cosmology problem,
  namely the analysis of cosmic microwave background data, where Bayesian inference
  of "noise" parameters means constraining models of the evolution of the Universe.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: heurtel-depeiges24a
month: 0
tex_title: 'Listening to the noise: Blind Denoising with {G}ibbs Diffusion'
firstpage: 18284
lastpage: 18304
page: 18284-18304
order: 18284
cycles: false
bibtex_author: Heurtel-Depeiges, David and Margossian, Charles and Ohana, Ruben and
  R\'{e}galdo-Saint Blancard, Bruno
author:
- given: David
  family: Heurtel-Depeiges
- given: Charles
  family: Margossian
- given: Ruben
  family: Ohana
- given: Bruno
  family: Régaldo-Saint Blancard
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/heurtel-depeiges24a/heurtel-depeiges24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
