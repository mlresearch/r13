---
abstract: 'We present a scalable Bayesian model for low-rank factorization of massive
  tensors with binary observations. The proposed model has the following key properties:
  (1) in contrast to the models based on logistic or probit likelihood, using a zero-truncated
  Poisson likelihood for binary data allows our model to scale up in the number of
  ones in the tensor, without sacrificing on the quality of the results; (2) side-information
  in form of binary pairwise relationships (e.g., an adjacency network) between objects
  in any tensor mode can also be leveraged, which can be especially useful in “cold-start”
  settings; and (3) the model admits simple inference via batch, as well as online
  MCMC; the latter allows us to scale up even for dense binary data (i.e., when the
  number of ones in the tensor/network is also massive). In addition, non-negative
  factor matrices in our model provide easy interpretability, and the tensor rank
  is inferred from data. We apply our model on several real-world massive binary tensors,
  and on massive binary tensors with binary mode-network(s) as side-information.'
title: Zero-Truncated Poisson Model for Scalable Bayesian Factorization of Massive
  Binary Tensors with Mode-Networks
year: '2015'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: university15v
month: 0
tex_title: Zero-Truncated {P}oisson Model for Scalable {B}ayesian Factorization of
  Massive Binary Tensors with Mode-Networks
firstpage: 950
lastpage: 959
page: 950-959
order: 950
cycles: false
bibtex_author: University, Changwei Hu Duke and University, Piyush Rai Duke and University,
  Lawrence Carin Duke
author:
- given: Changwei Hu Duke
  family: University
- given: Piyush Rai Duke
  family: University
- given: Lawrence Carin Duke
  family: University
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
pdf: https://raw.githubusercontent.com/mlresearch/r13/main/assets/university15v/university15v.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
