+++
title = "ALT 2020"


date = 2019-09-20T00:00:00
lastmod = 2019-09-20T00:00:00
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

Our paper [**Don’t Jump Through Hoops and Remove Those Loops: SVRG and Katyusha are Better Without the Outer Loop**](https://arxiv.org/pdf/1901.08689.pdf), joint work with [**Dmitry Kovalev**](https://www.dmitry-kovalev.com/) and [**Peter Richtarik**](https://richtarik.org/), got accepted to the ALT 2020. The conference takes place from 8-11th February at San Diego, California.

Abstract:

The stochastic variance-reduced gradient method (__SVRG__) and its accelerated variant (__Katyusha__) have attracted enormous attention in the machine learning community in the last few years due to their superior theoretical properties and empirical behaviour on training supervised machine learning models via the empirical risk minimization paradigm. A key structural element in both of these methods is the inclusion of an outer loop at the beginning of which a full pass over the training data is made in order to compute the exact gradient, which is then used in an inner loop to construct a variance-reduced estimator of the gradient using new stochastic gradient information. In this work we design loopless variants of both of these methods. In particular, we remove the outer loop and replace its function by a coin flip performed in each iteration designed to trigger, with a small probability , the computation of the gradient. We prove that the new methods enjoy the same superior theoretical convergence properties as the original methods. For loopless __SVRG__, the same rate is obtained for a large interval of coin flip probabilities, including the probability $\frac{1}{n}$, where $n$ is the number of functions. This is the first result where a variant of __SVRG__ is shown to converge with the same rate without the need for the algorithm to know the condition number, which is often unknown or hard to estimate correctly. We demonstrate through numerical experiments that the loopless methods can have superior and more robust practical behavior.
