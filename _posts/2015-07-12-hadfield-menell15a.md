---
abstract: A bandit superprocess is a decision problem composed from multiple independent
  Markov decision processes (MDPs), coupled only by the constraint that, at each time
  step, the agent may act in only one of the MDPs. Multitasking problems of this kind
  are ubiquitous in the real world, yet very little is known about them from a computational
  viewpoint, beyond the basic observation that optimal policies for the superprocess
  may prescribe actions that would be suboptimal for an MDP considered in isolation.
  (This observation implies that many applications of sequential decision analysis
  in practice are technically incorrect, since the decision problem being solved is
  typically part of a larger, unstated bandit superprocess.) The paper summarizes
  the state-of-the-art in the theory of bandit superprocesses and contributes a novel
  upper bound on the global value function of a bandit superprocess, defined in terms
  of a direct relaxation of the arms. The bound is equivalent to an existing bound
  (the Whittle integral) and so provides insight into an otherwise opaque formula.
  We provide an algorithm to compute this bound and use it to derive the first practical
  algorithms to select optimal actions in bandit superprocesses. The algorithm operates
  by repeatedly establishing dominance relations between actions using upper and lower
  bounds on action values. Experiments indicate that the algorithm’s run-time compares
  very favorably to other possible algorithms designed for more general factored MDPs.
title: 'Multitasking: Optimal Planning for Bandit Superprocesses'
year: '2015'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hadfield-menell15a
month: 0
tex_title: 'Multitasking: Optimal Planning for Bandit Superprocesses'
firstpage: 920
lastpage: 929
page: 920-929
order: 920
cycles: false
bibtex_author: Hadfield-Menell, Dylan and Russell, Stuart
author:
- given: Dylan
  family: Hadfield-Menell
- given: Stuart
  family: Russell
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
pdf: https://raw.githubusercontent.com/mlresearch/r13/main/assets/hadfield-menell15a/hadfield-menell15a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
