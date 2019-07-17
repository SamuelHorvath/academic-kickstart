+++
title = "New paper out"


date = 2019-01-24T00:00:00
lastmod = 2019-01-24T00:00:00
draft = false
math = true

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

tags = []
summary = "[**Don't Jump Through Hoops and Remove Those Loops: SVRG and Katyusha are Better Without the Outer Loop**](https://arxiv.org/pdf/1901.08689.pdf)"

+++

Our new paper **Don't Jump Through Hoops and Remove Those Loops: SVRG and Katyusha are Better Without the Outer Loop** is now available on the arxiv. This is the joint work with [**Dmitry Kovalev**](https://dakovalev1.github.io/) and my supervisor [**Peter Richtarik**](https://richtarik.org/).

Abstract:

The stochastic variance-reduced gradient method (SVRG) and its accelerated variant (Katyusha) have attracted enormous attention in the machine learning community in the last few years due to their superior theoretical properties and empirical behaviour on training supervised machine learning models via the empirical risk minimization paradigm. A key structural element in both of these methods is the inclusion of an outer loop at the beginning of which a full pass over the training data is made in order to compute the exact gradient, which is then used to construct a variance-reduced estimator of the gradient. In this work we design *loopless variants* of both of these methods. In particular, we remove the outer loop and replace its function by a coin flip performed in each iteration designed to trigger, with a small probability, the computation of the gradient. We prove that the new methods enjoy the same superior theoretical convergence properties as the original methods. However, we demonstrate through numerical experiments that our methods have substantially superior practical behavior.
