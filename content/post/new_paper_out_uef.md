+++
title = "New paper out"


date = 2020-06-22T00:00:00
lastmod = 2020-06-22T00:00:00
draft = false
math = true

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

tags = []
summary = "[**A Better Alternative to Error Feedback for Communication-Efficient Distributed Learning**](https://arxiv.org/pdf/2006.11077.pdf)"

+++

Our new paper **A Better Alternative to Error Feedback for Communication-Efficient Distributed Learning** is now available on the arXiv. This is a joint work  with my supervisor [**Peter Richtarik**](https://richtarik.org/).

Abstract:

Modern large-scale machine learning applications require stochastic optimization algorithms to be implemented on distributed compute systems. A key bottleneck of such systems is the communication overhead for exchanging information across the workers, such as stochastic gradients. Among the many techniques proposed to remedy this issue, one of the most successful is the framework of compressed communication with error feedback (EF). EF remains the only known technique that can deal with the error induced by contractive compressors which are not unbiased, such as Top-$K$.  In this paper, we propose a new and theoretically and practically better alternative to EF for dealing with contractive compressors. In particular, we propose a construction which can transform any contractive compressor into an induced unbiased compressor. Following this transformation, existing methods able to work with unbiased compressors can be applied. We show that our approach leads to vast improvements over EF, including reduced memory requirements, better communication complexity guarantees and fewer assumptions. We further extend our results to federated learning with partial participation following an arbitrary distribution over the nodes, and demonstrate the benefits thereof. We perform several numerical experiments which validate our theoretical findings.
