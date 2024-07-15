---
title: 'MaxMin-RLHF: Alignment with Diverse Human Preferences'
openreview: 8tzjEMF0Vq
abstract: Reinforcement Learning from Human Feedback (RLHF) aligns language models
  to human preferences by employing a singular reward model derived from preference
  data. However, the single reward model overlooks the rich diversity of human preferences
  inherent in data collected from multiple users. In this work, we first derive an
  impossibility result of alignment with single reward RLHF, thereby highlighting
  its insufficiency in representing diverse human preferences. Next, we propose to
  learn a mixture of reward models via an expectation-maximization algorithm and solve
  a MaxMin alignment objective inspired by the Egalitarian principle in social choice
  theory to better honor diverse human preferences. We present comprehensive experimental
  results on small-scale (GPT-2) and large-scale language (with Tulu2-7B)) and show
  the efficacy of the proposed approach in the presence of diversity among human preferences.
  We remark that our findings in this work are not only limited to language models
  but also extend to reinforcement learning in general.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chakraborty24b
month: 0
tex_title: "{M}ax{M}in-{RLHF}: Alignment with Diverse Human Preferences"
firstpage: 6116
lastpage: 6135
page: 6116-6135
order: 6116
cycles: false
bibtex_author: Chakraborty, Souradip and Qiu, Jiahao and Yuan, Hui and Koppel, Alec
  and Manocha, Dinesh and Huang, Furong and Bedi, Amrit and Wang, Mengdi
author:
- given: Souradip
  family: Chakraborty
- given: Jiahao
  family: Qiu
- given: Hui
  family: Yuan
- given: Alec
  family: Koppel
- given: Dinesh
  family: Manocha
- given: Furong
  family: Huang
- given: Amrit
  family: Bedi
- given: Mengdi
  family: Wang
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
pdf: https://raw.githubusercontent.com/mlresearch/v235/main/assets/chakraborty24b/chakraborty24b.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
