---
abstract: Conditioned Belief Propagation (CBP) is an algorithm for approximate inference
  in probabilistic graphical models. It works by conditioning on a subset of variables,
  and solving the remainder using loopy Belief Propagation. Unfortunately, CBP’s runtime
  scales exponentially in the number of conditioned variables. Locally Conditioned
  Belief Propagation (LCBP) approximates the results of CBP by treating conditions
  locally, and in this way avoids the exponential blow-up. We formulate LCBP as a
  variational optimization problem and derive a set of update equations that can be
  used to solve it. We show empirically that LCBP delivers results that are close
  to those obtained from CBP, while the computational cost scales favorably with problem
  size.
title: Locally Conditioned Belief Propagation
year: '2015'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: university15i
month: 0
tex_title: Locally Conditioned Belief Propagation
firstpage: 477
lastpage: 486
page: 477-486
order: 477
cycles: false
bibtex_author: University, Thomas Geier Ulm and University, Felix Richter Ulm and
  University, Susanne Biundo Ulm
author:
- given: Thomas Geier Ulm
  family: University
- given: Felix Richter Ulm
  family: University
- given: Susanne Biundo Ulm
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
pdf: https://raw.githubusercontent.com/mlresearch/r13/main/assets/university15i/university15i.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
