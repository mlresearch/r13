---
abstract: Monte Carlo tree search (MCTS) algorithms can encounter difficulties when
  solving Markov decision problems (MDPs) in which the outcomes of actions are highly
  stochastic. This stochastic branching can be reduced through state abstraction.
  In online planning with a time budget, there is a complex tradeoff between the loss
  in performance due to overly coarse abstraction versus the gain in performance from
  reducing the problem size. We find empirically that very coarse and unsound abstractions
  often outperform sound abstractions for practical planning budgets. Motivated by
  this, we propose a progressive abstraction refinement algorithm that refines an
  initially coarse abstraction during search in order to match the abstraction granularity
  to the sample budget. Our experiments demonstrate the strong performance of search
  with coarse abstractions, and show that our proposed algorithm combines the benefits
  of coarse abstraction at small sample budgets with the ability to exploit larger
  budgets for further performance gains.
title: Progressive Abstraction Refinement for Sparse Sampling
year: '2015'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: university15d
month: 0
tex_title: Progressive Abstraction Refinement for Sparse Sampling
firstpage: 209
lastpage: 218
page: 209-218
order: 209
cycles: false
bibtex_author: University, Jesse Hostetler Oregon State and University, Alan Fern
  Oregon State and University, Thomas Dietterich Oregon State
author:
- given: Jesse Hostetler Oregon State
  family: University
- given: Alan Fern Oregon State
  family: University
- given: Thomas Dietterich Oregon State
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
pdf: https://raw.githubusercontent.com/mlresearch/r13/main/assets/university15d/university15d.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
