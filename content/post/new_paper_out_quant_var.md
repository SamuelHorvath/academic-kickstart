+++
title = "New paper out"


date = 2019-04-08T00:00:00
lastmod = 2019-04-08T00:00:00
draft = false
math = true

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

tags = []
summary = "[**Stochastic Distributed Learning with Gradient Quantization and Variance Reduction**](https://arxiv.org/pdf/1904.05115.pdf)"

+++

Our new paper **Stochastic Distributed Learning with Gradient Quantization and Variance Reduction** will be soon available on the arxiv. This is the joint work with [**Dmitry Kovalev**](https://dakovalev1.github.io/), [**Konstantin Mishchenko**](https://konstmish.github.io/), [**Sebastian Stich**](https://www.sstich.ch/), and my supervisor [**Peter Richtarik**](https://richtarik.org/).

Abstract:

We consider distributed optimization where the objective function is spread among different devices, each sending incremental model updates to a central server. To alleviate the communication bottleneck, recent work proposed various schemes to compress (e.g.\ quantize or sparsify) the gradients, thereby introducing additional variance $\omega \geq 1$ that might slow down convergence. For strongly convex functions with condition number $\kappa$ distributed among $n$ machines:

 * we give a scheme that converges in $\mathcal{O}((\kappa + \kappa \frac{\omega}{n} + \omega)$$\log (1/\epsilon))$ steps to a neighborhood of the optimal solution. For objective functions with a finite-sum structure, each worker having less than $m$ components,
 * we present novel variance reduced schemes that converge in $\mathcal{O}((\kappa + \kappa \frac{\omega}{n} + \omega + m)\log(1/\epsilon))$ steps to arbitrary accuracy $\epsilon > 0$. These are the first methods that achieve linear convergence for arbitrary quantized updates,

 * we give analysis for the weakly convex and non-convex cases,
 * we verify in experiments that our novel variance reduced schemes are more efficient than the baselines.
