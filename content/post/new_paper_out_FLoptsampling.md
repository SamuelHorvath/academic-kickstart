+++
title = "New paper out"


date = 2020-10-26T00:00:00
lastmod = 2020-10-26T00:00:00
draft = false
math = true

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

tags = []
summary = "[**Optimal Client Sampling for Federated Learning**](https://arxiv.org/abs/2010.13723)"

+++

Our new paper **Optimal Client Sampling for Federated Learning** is now available on the arXiv. This is the joint work with **Wenlin Chen** and [**Peter Richtarik**](https://richtarik.org/).

Abstract:

It is well understood that client-master communication can be a primary bottleneck in Federated Learning. In this work, we address this issue with a novel client subsampling scheme, where we restrict the number of clients  allowed to communicate their updates back to the master node. In each communication round, all participated clients compute their updates, but only the ones with "important" updates communicate back to the master. We show that importance can be measured using only the norm of the update and we give a formula for optimal client participation. This formula minimizes the distance between the full update, where all clients participate, and our limited update, where the number of participating clients  is restricted. In addition, we provide a simple algorithm that approximates the optimal formula for client participation which only requires secure aggregation and thus does not compromise client privacy. We show
 both theoretically and empirically
that our approach leads to superior performance for Distributed _SGD_ (_DSGD_) and Federated Averaging (_FedAvg_) compared to the baseline where participating clients are sampled uniformly. Finally, our approach is orthogonal to and compatible with existing methods for reducing communication overhead, such as local methods and communication compression methods.
