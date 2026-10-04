---
abstract: We develop hierarchical Poisson matrix factorization (HPF), a novel method
  for providing users with high quality recommendations based on implicit feedback,
  such as views, clicks, or purchases. In contrast to existing recommendation models,
  HPF has a number of desirable properties. First, we show that HPF more accurately
  captures the long-tailed user activity found in most consumption data by explicitly
  considering the fact that users have finite attention budgets. This leads to better
  estimates of users’ latent preferences, and therefore superior recommendations,
  compared to competing methods. Second, HPF learns these latent factors by only explicitly
  considering positive examples, eliminating the often costly step of generating artificial
  negative examples when fitting to implicit data. Third, HPF is more than just one
  method—it is the simplest in a class of probabilistic models with these properties,
  and can easily be extended to include more complex structure and assumptions. We
  develop a variational algorithm for approximate posterior inference for HPF that
  scales up to large data sets, and we demonstrate its performance on a wide variety
  of real-world recommendation problems—users rating movies, listening to songs, reading
  scientific papers, and reading news articles. Our study reveals that hierarchical
  Poisson factorization definitively outperforms previous methods, including nonnegative
  matrix factorization, topic models, and probabilistic matrix factorization techniques.
title: Scalable Recommendation with Hierarchical Poisson Factorization
year: '2015'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: university15n
month: 0
tex_title: Scalable Recommendation with Hierarchical {P}oisson Factorization
firstpage: 624
lastpage: 633
page: 624-633
order: 624
cycles: false
bibtex_author: University, Prem Gopalan Princeton and Hofman, Jake and University,
  David Blei Columbia
author:
- given: Prem Gopalan Princeton
  family: University
- given: Jake
  family: Hofman
- given: David Blei Columbia
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
pdf: https://raw.githubusercontent.com/mlresearch/r13/main/assets/university15n/university15n.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
