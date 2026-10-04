---
abstract: 'We propose an efficient nonparametric strategy for learning a message operator
  in expectation propagation (EP), which takes as input the set of incoming messages
  to a factor node, and produces an outgoing message as output. This learned operator
  replaces the multivariate integral required in classical EP, which may not have
  an analytic expression. We use kernel-based regression, which is trained on a set
  of probability distributions representing the incoming messages, and the associated
  outgoing messages. The kernel approach has two main advantages: first, it is fast,
  as it is implemented using a novel two-layer random feature representation of the
  input message distributions; second, it has principled uncertainty estimates, and
  can be cheaply updated online, meaning it can request and incorporate new training
  data when it encounters inputs on which it is uncertain. In experiments, our approach
  is able to solve learning problems where a single message operator is required for
  multiple, substantially different data sets (logistic regression for a variety of
  classification problems), where the ability to accurately assess uncertainty and
  to efficiently and robustly update the message operator are essential.'
title: Kernel-Based Just-In-Time Learning for Passing Expectation Propagation Messages
year: '2015'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: jitkrittum15a
month: 0
tex_title: Kernel-Based Just-In-Time Learning for Passing Expectation Propagation
  Messages
firstpage: 722
lastpage: 731
page: 722-731
order: 722
cycles: false
bibtex_author: Jitkrittum, Wittawat and Gretton, Arthur and Heess, Nicolas and Eslami,
  S. M. Ali and Lakshminarayanan, Balaji and Sejdinovic, Dino and Szab{\'o}, Zolt{\'a}n
author:
- given: Wittawat
  family: Jitkrittum
- given: Arthur
  family: Gretton
- given: Nicolas
  family: Heess
- given: S. M. Ali
  family: Eslami
- given: Balaji
  family: Lakshminarayanan
- given: Dino
  family: Sejdinovic
- given: Zoltán
  family: Szabó
date: 2015-07-12
note: Reissued by PMLR on 04 October 2026.
address:
container-title: Proceedings of the 31st Conference on Uncertainty in Artificial Intelligence
volume: R13
genre: inproceedings
issued:
  date-parts:
  - 2015
  - 7
  - 12
pdf: https://raw.githubusercontent.com/mlresearch/r13/main/assets/jitkrittum15a/jitkrittum15a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
