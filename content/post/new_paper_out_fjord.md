+++
title = "New paper out"


date = 2021-02-28T00:00:00
lastmod = 2021-02-28T00:00:00
draft = false
math = true

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

tags = []
summary = "[**FjORD: Fair and Accurate Federated Learning under heterogeneous targets with Ordered Dropout**](https://arxiv.org/pdf/2102.13451.pdf)"

+++

Our new paper **FjORD: Fair and Accurate Federated Learning under heterogeneous targets with Ordered Dropout** is now available on the arXiv. This is a joint work with [**Stefanos Laskaridis**](https://stevelaskaridis.github.io/), [**Mario Almeida**](https://www.marioalmeida.com/), [**Ilias Leontiadis**](https://leontiadis.net/), [**Stylianos Venieris**](https://steliosven10.github.io/), and [**Nic Lane**](http://niclane.org/) from Samsung AI Centre, Cambridge, UK.

Abstract:

Federated Learning (FL) has been gaining significant traction across different ML tasks, ranging from vision to keyboard predictions. In large scale deployments, client heterogeneity is a fact, and constitutes a primary problem for fairness, significant efforts have been made into tackling statistical data heterogeneity, the diversity in the clients, termed as system heterogeneity, has remained largely unexplored. Current solutions either disregard a large portion of available devices or set a uniform limit on the model’s capacity, restricted by the least capable participants. In this work, we introduce Ordered Dropout, a mechanism that achieves an ordered, nested representation of knowledge in Neural Networks and enables the extraction of lower footprint submodels without the need of retraining. We further show that for linear maps our Ordered Dropout is equivalent to SVD. We employ this technique, along with a self-distillation methodology, in the realm of FL in a framework called FjORD. FjORD alleviates the problem of client system heterogeneity by tailoring the model width to the client’s capabilities. Extensive evaluation on both CNNs and RNNs across diverse modalities shows that FjORD consistently leads to significant performance gains over state-of-the-art baselines, while maintaining its nested structure.
