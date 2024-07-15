---
title: Trustless Audits without Revealing Data or Models
openreview: AtVtt9xsO1
abstract: There is an increasing conflict between business incentives to hide models
  and data as trade secrets, and the societal need for algorithmic transparency. For
  example, a rightsholder who currently wishes to know whether their copyrighted works
  have been used during training must convince the model provider to allow a third
  party to audit the model and data. Finding a mutually agreeable third party is difficult,
  and the associated costs often make this approach impractical. In this work, we
  show that it is possible to simultaneously allow model providers to keep their models
  and data secret while allowing other parties to trustlessly audit properties of
  the model and data. We do this by designing a protocol called ZkAudit in which model
  providers publish cryptographic commitments of datasets and model weights, alongside
  a zero-knowledge proof (ZKP) certifying that published commitments are derived from
  training the model. Model providers can then respond to audit requests by privately
  computing any function F of the dataset (or model) and releasing the output of F
  alongside another ZKP certifying the correct execution of F. To enable ZkAudit,
  we develop new methods of computing ZKPs for SGD on modern neural nets for recommender
  systems and image classification models capable of high accuracies on ImageNet.
  Empirically, we show it is possible to provide trustless audits of DNNs, including
  copyright, censorship, and counterfactual audits with little to no loss in accuracy.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: waiwitlikhit24a
month: 0
tex_title: Trustless Audits without Revealing Data or Models
firstpage: 49808
lastpage: 49821
page: 49808-49821
order: 49808
cycles: false
bibtex_author: Waiwitlikhit, Suppakit and Stoica, Ion and Sun, Yi and Hashimoto, Tatsunori
  and Kang, Daniel
author:
- given: Suppakit
  family: Waiwitlikhit
- given: Ion
  family: Stoica
- given: Yi
  family: Sun
- given: Tatsunori
  family: Hashimoto
- given: Daniel
  family: Kang
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/waiwitlikhit24a/waiwitlikhit24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
