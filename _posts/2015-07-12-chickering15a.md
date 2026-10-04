---
abstract: We introduce Selective Greedy Equivalence Search (SGES), a restricted version
  of Greedy Equivalence Search (GES). SGES retains the asymptotic correctness of GES
  but, unlike GES, has polynomial performance guarantees. In particular, we show that
  when data are sampled independently from a distribution that is perfect with respect
  to a DAG $\Gr$ defined over the observable variables then, in the limit of large
  data, SGES will identify $\Gr$’s equivalence class after a number of score evaluations
  that is (1) polynomial in the number of nodes and (2) exponential in various complexity
  measures including maximum-number-of-parents, maximum-clique-size, and a new measure
  called {\em v-width} that is necessarily not larger—and potentially much smaller—than
  the other two. More generally, we show that for any hereditary and equivalence-invariant
  property $\Pi$ known to hold in $\Gr$, we retain the large-sample optimality guarantees
  of GES even if we ignore any GES deletion operator that results in a state for which
  $\Pi$ does not hold in the common-descendants subgraph.
title: 'Selective Greedy Equivalence Search: Finding Optimal Bayesian Networks Using
  a Polynomial Number of Score Evaluations'
year: '2015'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chickering15a
month: 0
tex_title: 'Selective Greedy Equivalence Search: Finding Optimal {B}ayesian Networks
  Using a Polynomial Number of Score Evaluations'
firstpage: 771
lastpage: 779
page: 771-779
order: 771
cycles: false
bibtex_author: Chickering, Max and Meek, Chris
author:
- given: Max
  family: Chickering
- given: Chris
  family: Meek
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
pdf: https://raw.githubusercontent.com/mlresearch/r13/main/assets/chickering15a/chickering15a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
