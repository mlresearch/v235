---
title: 'Robust CLIP: Unsupervised Adversarial Fine-Tuning of Vision Embeddings for
  Robust Large Vision-Language Models'
openreview: WLPhywf1si
abstract: Multi-modal foundation models like OpenFlamingo, LLaVA, and GPT-4 are increasingly
  used for various real-world tasks. Prior work has shown that these models are highly
  vulnerable to adversarial attacks on the vision modality. These attacks can be leveraged
  to spread fake information or defraud users, and thus pose a significant risk, which
  makes the robustness of large multi-modal foundation models a pressing problem.
  The CLIP model, or one of its variants, is used as a frozen vision encoder in many
  large vision-language models (LVLMs), e.g. LLaVA and OpenFlamingo. We propose an
  unsupervised adversarial fine-tuning scheme to obtain a robust CLIP vision encoder,
  which yields robustness on all vision down-stream tasks (LVLMs, zero-shot classification)
  that rely on CLIP. In particular, we show that stealth-attacks on users of LVLMs
  by a malicious third party providing manipulated images are no longer possible once
  one replaces the original CLIP model with our robust one. No retraining or fine-tuning
  of the down-stream LVLMs is required. The code and robust models are available on
  GitHub.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: schlarmann24a
month: 0
tex_title: 'Robust {CLIP}: Unsupervised Adversarial Fine-Tuning of Vision Embeddings
  for Robust Large Vision-Language Models'
firstpage: 43685
lastpage: 43704
page: 43685-43704
order: 43685
cycles: false
bibtex_author: Schlarmann, Christian and Singh, Naman Deep and Croce, Francesco and
  Hein, Matthias
author:
- given: Christian
  family: Schlarmann
- given: Naman Deep
  family: Singh
- given: Francesco
  family: Croce
- given: Matthias
  family: Hein
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/schlarmann24a/schlarmann24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
