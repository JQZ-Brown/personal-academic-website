---
abstract: We consider the problem of estimating a sparse Gaussian Graphical
  Model with a special graph topological structure and more than a million
  variables. Most previous scalable estimators still contain expensive
  calculation steps (e.g., matrix inversion or Hessian matrix calculation) and
  become infeasible in high-dimensional scenarios, where p (number of variables)
  is larger than n (number of samples). To overcome this challenge, we propose a
  novel method, called Fast and Scalable Inverse Covariance Estimator by
  Thresholding (FST). FST first obtains a graph structure by applying a
  generalized threshold to the sample covariance matrix. Then, it solves
  multiple block-wise subproblems via element-wise thresholding. By using matrix
  thresholding instead of matrix inversion as the computational bottleneck, FST
  reduces its computational complexity to a much lower order of magnitude
  (O(p2)). We show that FST obtains the same sharp convergence rate O(√(log
  max{p, n}/n) as other state-of-the-art methods. We validate the method
  empirically, on multiple simulated datasets and one real-world dataset, and
  show that FST is two times faster than the four baselines while achieving a
  lower error rate under both Frobenius-norm and max-norm.
slides: ""
url_pdf: ""
publication_types:
  - "1"
authors:
  - **Jiaqi Zhang**
  - Meng Wang
  - Qinchi Li
  - Sen Wang
  - Xiaojun Chang
  - Beilun Wang
author_notes: []
publication: Proceedings of the Twenty-Ninth International Joint Conference on
  Artificial Intelligence Main track
summary: ""
url_dataset: ""
url_project: ""
publication_short: IJCAI 2020
url_source: ""
url_video: ""
title: Quadratic Sparse Gaussian Graphical Model Estimation Method for Massive
  Variables
doi: 10.24963/ijcai.2020/410
featured: false
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: poster.jpg
date: 2020-07-01T16:00:53.476Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---
