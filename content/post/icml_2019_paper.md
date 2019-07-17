+++
title = "ICML 2019"


date = 2019-05-10T00:00:00
lastmod = 2019-05-10T00:00:00
draft = false
math = true

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

tags = []
summary = "We get one paper accepted!"

[header]
image = ""
caption = ""
+++

Our paper [**Nonconvex Variance Reduced Optimization with Arbitrary Sampling**](https://arxiv.org/pdf/1809.04146.pdf), joint work with [**Peter Richtarik**](https://richtarik.org/), got accepted to the ICML 2019. The conference takes place from 9-15th June at Long Beach, California.

Abstract:

We provide the first importance sampling variants of variance reduced algorithms for empirical risk minimization with non-convex loss functions. In particular, we analyze non-convex versions of
SVRG, SAGA and SARAH. Our methods have the capacity to speed up the training process by  an order of magnitude compared to the state of the art on real datasets. Moreover, we also improve upon current mini-batch analysis of these methods by proposing  importance sampling for minibatches in this setting. Surprisingly, our approach can in some regimes lead to superlinear speedup with respect to the minibatch size, which is not usually present in stochastic optimization. All the above results follow from a general analysis of the methods which works with arbitrary sampling, i.e., fully general randomized strategy for the selection of subsets of examples to be sampled in each iteration. Finally, we also perform a novel importance sampling analysis of SARAH in the convex setting.


Poster:

![DS3_poster](/img/Poster-DS3-small.png)
