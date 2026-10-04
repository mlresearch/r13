---
abstract: Recently it was shown that the problem of Maximum Inner Product Search (MIPS)
  is efficient and it admits provably sub-linear hashing algorithms. In \cite{Proc:Shrivastava_NIPS14},
  the authors use asymmetric transformations which convert the problem of approximate
  MIPS into the problem of approximate near neighbor search which can be efficiently
  solved using L2-LSH. In this work, we revisit the problem of MIPS and argue that
  the quantizations used in L2-LSH is suboptimal for MIPS compared to signed random
  projections (SRP) which is another popular hashing scheme for cosine similarity
  (or correlations). Based on this observation, we provide different asymmetric transformations
  which convert the problem of approximate MIPS into the problem amenable to SRP instead
  of L2-LSH. An additional advantage of our scheme is that we also obtain LSH type
  space partitioning which is not possible with the existing scheme. Our theoretical
  analysis show that the new scheme is significantly better than the original scheme
  for MIPS. Experimental evaluations strongly support the theoretical findings. We
  also provide the first empirical comparison that shows the superiority of hashing
  over tree based methods \cite{Proc:Ram_KDD12} for MIPS.
title: Improved Asymmetric Locality Sensitive Hashing (ALSH) for Maximum Inner Product
  Search (MIPS)
year: '2015'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: university15e
month: 0
tex_title: Improved Asymmetric Locality Sensitive Hashing ({ALSH}) for Maximum Inner
  Product Search ({MIPS})
firstpage: 259
lastpage: 268
page: 259-268
order: 259
cycles: false
bibtex_author: University, Anshumali Shrivastava Cornell and University, Ping Li Rutgers
author:
- given: Anshumali Shrivastava Cornell
  family: University
- given: Ping Li Rutgers
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
pdf: https://raw.githubusercontent.com/mlresearch/r13/main/assets/university15e/university15e.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
