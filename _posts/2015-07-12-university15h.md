---
abstract: In this paper, we study the problem of empirical loss minimization with
  l2-regularization in distributed settings with significant communication cost. Stochastic
  gradient descent (SGD) and its variants are popular techniques for solving these
  problems in large-scale applications. However, the communication cost of these techniques
  is usually high, thus leading to considerable performance degradation. We introduce
  a novel approach to reduce the communication cost while retaining good convergence
  properties. The key to our approach is the construction of a small summary of the
  data, called coreset, at each iteration and solve an easy optimization problem based
  on the coreset. We present a general framework for analyzing coreset-based optimization
  and provide interesting insights into existing algorithms from this perspective.
  We then propose a new coreset construction and provide its convergence analysis
  for a wide class of problems that include logistic regression and support vector
  machines. We demonstrate the performance of our algorithm on real-world datasets
  and compare it against state-of-the-art algorithms.
title: Communication Efficient Coresets for Empirical Loss Minimization
year: '2015'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: university15h
month: 0
tex_title: Communication Efficient Coresets for Empirical Loss Minimization
firstpage: 437
lastpage: 446
page: 437-446
order: 437
cycles: false
bibtex_author: University, Sashank Jakkam Reddi Carnegie Mellon and Smola, Barnabas
  Poczos Alex
author:
- given: Sashank Jakkam Reddi Carnegie Mellon
  family: University
- given: Barnabas Poczos Alex
  family: Smola
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
pdf: https://raw.githubusercontent.com/mlresearch/r13/main/assets/university15h/university15h.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
