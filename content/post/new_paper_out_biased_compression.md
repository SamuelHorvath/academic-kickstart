+++
title = "New paper out"


date = 2020-03-02T00:00:00
lastmod = 2020-03-02T00:00:00
draft = false
math = true

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

tags = []
summary = "[**On Biased Compression for Distributed Learning**](https://arxiv.org/pdf/2002.12410.pdf)"

+++

Our new paper **On Biased Compression for Distributed Learning** is now available on the arXiv. This is a joint work  with [**Aleksandr Beznosikov**](https://scholar.google.com/citations?user=hVVJR-sAAAAJ&hl=ru), [**Mher Safaryan**](https://mher-safaryan.github.io/)  and my supervisor [**Peter Richtarik**](https://richtarik.org/).

Abstract:

In the last few years, various communication compression techniques have emerged as an indispensable tool helping to alleviate the communication bottleneck in distributed learning. However, despite the fact biased compressors often show superior performance in practice when compared to the much more studied and understood unbiased compressors, very little is known about them. In this work we study three classes of biased compression operators, two of which are new, and their performance when applied to (stochastic) gradient descent and distributed (stochastic) gradient descent. We show for the first time that biased compressors can lead to linear convergence rates both in the single node and distributed settings. Our distributed SGD method enjoys the ergodic rate $\mathcal{O}\left(\frac{\delta Le^{-K}}{\mu} + \frac{C+D}{K\mu}\right)$ , where $\delta$ is a compression parameter which grows when more compression is applied, $L$ and $\mu$ are the smoothness and strong convexity constants, $C$ captures stochastic gradient noise ($C = 0$ if full gradients are computed on each node) and $D$ captures the variance of the gradients at the optimum ($D = 0$ for over-parameterized models). Further, via a theoretical study of several synthetic and empirical distributions of communicated gradients, we shed light on why and by how much biased compressors outperform their unbiased variants. Finally, we propose a new highly performing biased compressor—combination of Top-k and natural dithering—which in our experiments outperforms all other compression techniques.
