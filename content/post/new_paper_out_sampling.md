+++
title = "New paper out"


date = 2018-09-11T00:00:00
lastmod = 2018-09-11T00:00:00
draft = false
math = true

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

tags = []
summary = "[**Nonconvex Variance Reduced Optimization with Arbitrary Sampling**](https://arxiv.org/pdf/1809.04146.pdf)"

+++

Our paper is now available on the arxiv. A poster based on the results of this paper won [the Best Poster]({{% ref "post/dss_2018/index.md" %}}) at Data Science Summer School in Paris, 2018.

Abstract:

We provide the first importance sampling variants of variance reduced algorithms for empirical risk minimization with non-convex loss functions. In particular, we analyze non-convex versions of
SVRG, SAGA and SARAH. Our methods have the capacity to speed up the training process by  an order of magnitude compared to the state of the art on real datasets. Moreover, we also improve upon current mini-batch analysis of these methods by proposing  importance sampling for minibatches in this setting. Surprisingly, our approach can in some regimes lead to superlinear speedup with respect to the minibatch size, which is not usually present in stochastic optimization. All the above results follow from a general analysis of the methods which works with arbitrary sampling, i.e., fully general randomized strategy for the selection of subsets of examples to be sampled in each iteration. Finally, we also perform a novel importance sampling analysis of SARAH in the convex setting.


Poster:

![DS3_poster](/img/Poster-DS3-small.png)
