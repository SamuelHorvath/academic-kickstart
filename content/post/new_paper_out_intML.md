+++
title = "New paper out"


date = 2019-05-27T00:00:00
lastmod = 2019-05-27T00:00:00
draft = false
math = true

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

tags = []
summary = "[**Natural Compression for Distributed Deep Learning**](https://arxiv.org/pdf/1905.10988.pdf)"

+++

Our new paper **Natural Compression for Distributed Deep Learning** is now available on the arxiv. This is the joint work with [**Chen-Yu Ho**](https://www.chenyuho.com/), **Ludovit Horvath**, **Atal Sahu**, [**Marco Canini**](https://mcanini.github.io/) and [**Peter Richtarik**](https://richtarik.org/).

Abstract:

Due to their hunger for big data, modern deep learning models are trained in parallel, often in distributed environments, where communication of model updates is the bottleneck. Various update compression (e.g., quantization, sparsification, dithering) techniques have been proposed in recent years as a successful tool to alleviate this problem. In this work, we introduce a new, remarkably simple and theoretically and practically effective compression technique, which we call *natural compression* $\mathcal{NC}$. Our technique is applied individually to all entries of the to-be-compressed update vector and works by randomized rounding to the nearest (negative or positive) power of two. $\mathcal{NC}$ is "natural" since the nearest power of two of a real expressed as a float can be obtained without any computation, simply by ignoring the mantissa. We show that compared to no compression,  $\mathcal{NC}$ increases the second moment of the compressed vector by the tiny factor  $\frac{9}{8}$ only, which means that the effect of $\mathcal{NC}$ on the convergence speed of popular training algorithms, such as distributed SGD, is negligible.  However, the communications savings enabled by $\mathcal{NC}$ are substantial, leading to  _$3$-$4$x_ improvement in overall theoretical running time}. For applications requiring more aggressive compression, we generalize $\mathcal{NC}$ to _natural dithering_, which we prove is **exponentially better** than the immensely popular random dithering technique. Our compression operators can be used on their own or in combination with existing operators for a more aggressive combined effect. Finally, we show that $\mathcal{NC}$ is particularly effective for the in-network aggregation (INA) framework for distributed training, where the update aggregation is done on a switch, which can only perform integer computations.
