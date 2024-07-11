---
title: 'ArtWhisperer: A Dataset for Characterizing Human-AI Interactions in Artistic
  Creations'
openreview: MKzgqtRtGY
abstract: In this work, we investigate how people use text-to-image models to generate
  desired target images. To study this interaction, we created ArtWhisperer, an online
  game where users are given a target image and are tasked with iteratively finding
  a prompt that creates a similar-looking image as the target. Through this game,
  we recorded over 50,000 human-AI interactions; each interaction corresponds to one
  text prompt created by a user and the corresponding generated image. The majority
  of these are repeated interactions where a user iterates to find the best prompt
  for their target image, making this a unique sequential dataset for studying human-AI
  collaborations. In an initial analysis of this dataset, we identify several characteristics
  of prompt interactions and user strategies. People submit diverse prompts and are
  able to discover a variety of text descriptions that generate similar images. Interestingly,
  prompt diversity does not decrease as users find better prompts. We further propose
  a new metric to quantify AI model <em>steerability</em> using our dataset. We define
  steerability as the expected number of interactions required to adequately complete
  a task. We estimate this value by fitting a Markov chain for each target task and
  calculating the expected time to reach an adequate score. We quantify and compare
  AI steerability across different types of target images and two different models,
  finding that images of cities and nature are more steerable than artistic and fantasy
  images. We also evaluate popular vision-language models to assess their image understanding
  and ability to incorporate feedback. These findings provide insights into human-AI
  interaction behavior, present a concrete method of assessing AI steerability, and
  demonstrate the general utility of the ArtWhisperer dataset.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: vodrahalli24a
month: 0
tex_title: "{A}rt{W}hisperer: A Dataset for Characterizing Human-{AI} Interactions
  in Artistic Creations"
firstpage: 49627
lastpage: 49654
page: 49627-49654
order: 49627
cycles: false
bibtex_author: Vodrahalli, Kailas and Zou, James
author:
- given: Kailas
  family: Vodrahalli
- given: James
  family: Zou
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
pdf: https://proceedings.mlr.press/v235/vodrahalli24a/vodrahalli24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
