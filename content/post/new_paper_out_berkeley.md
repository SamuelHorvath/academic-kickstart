+++
title = "New paper out"


date = 2020-02-12T00:00:00
lastmod = 2020-02-12T00:00:00
draft = false
math = true

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

tags = []
summary = "[**Adaptivity of Stochastic Gradient Methods for Nonconvex Optimization**](https://arxiv.org/pdf/2002.tbd.pdf)"

+++

Our new paper **Adaptivity of Stochhastic Gradient Methods for Nonconvex Optimization** is now available on the arxiv. This project originated in May 2019 while I was visiting prof. [**Michael I. Jordan**](https://people.eecs.berkeley.edu/~jordan/) at Berkeley and is the joint work with [**Lihua Lei**](https://lihualei71.github.io/), that time PhD student at Berkeley, and my supervisor [**Peter Richtarik**](https://richtarik.org/).

Abstract:

Adaptivity is an important yet under-studied property in modern optimization theory. The gap between the state-of-the-art theory and the current practice is striking in that algorithms with desirable theoretical guarantees typically involve drastically different settings of hyperparameters, such as step-size schemes and batch sizes, in different regimes. Despite the appealing theoretical results, such divisive strategies provide little, if any, insight to practitioners to select algorithms that work broadly without tweaking the hyperparameters. In this work, blending the "geometrization" technique introduced by Lei & Jordan, 2016, and the __SARAH__ algorithm of Nguyen et al., we propose the Geometrized  __SARAH__ algorithm for non-convex finite-sum and stochastic optimization. Our algorithm is proved to achieve adaptivity to both the magnitude of the target accuracy and the Polyak-Lojasiewicz (PL) constant, if present. In addition, it achieves the best-available convergence rate for non-PL objectives simultaneously while outperforming existing algorithms for PL objectives.
