---
supplementary: http://proceedings.mlr.press/v48/mirzasoleiman16-supp.pdf
title: 'Fast Constrained Submodular Maximization: Personalized Data Summarization'
abstract: 'Can we summarize multi-category data based on user preferences in a scalable
  manner? Many utility functions used for data summarization satisfy submodularity,
  a natural diminishing returns property. We cast personalized data summarization
  as an instance of a general submodular maximization problem subject to multiple
  constraints. We develop the first practical and FAst coNsTrained submOdular Maximization
  algorithm, FANTOM, with strong theoretical guarantees. FANTOM maximizes a submodular
  function (not necessarily monotone) subject to intersection of a p-system and l
  knapsacks constrains. It achieves a (1 + ε)(p + 1)(2p + 2l + 1)/p approximation
  guarantee with only O(nrp log(n)/ε) query complexity (n and r indicate the size
  of the ground set and the size of the largest feasible solution, respectively).
  We then show how we can use FANTOM for personalized data summarization. In particular,
  a p-system can model different aspects of data, such as categories or time stamps,
  from which the users choose. In addition, knapsacks encode users’ constraints including
  budget or time. In our set of experiments, we consider several concrete applications:
  movie recommendation over 11K movies, personalized image summarization with 10K
  images, and revenue maximization on the YouTube social networks with 5000 communities.
  We observe that FANTOM constantly provides the highest utility against all the baselines.'
layout: inproceedings
series: Proceedings of Machine Learning Research
id: mirzasoleiman16
month: 0
tex_title: 'Fast Constrained Submodular Maximization: Personalized Data Summarization'
firstpage: 1358
lastpage: 1367
page: 1358-1367
order: 1358
cycles: false
author:
- given: Baharan
  family: Mirzasoleiman
- given: Ashwinkumar
  family: Badanidiyuru
- given: Amin
  family: Karbasi
date: 2016-06-11
address: New York, New York, USA
publisher: PMLR
container-title: Proceedings of The 33rd International Conference on Machine Learning
volume: '48'
genre: inproceedings
issued:
  date-parts:
  - 2016
  - 6
  - 11
pdf: http://proceedings.mlr.press/v48/mirzasoleiman16.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
