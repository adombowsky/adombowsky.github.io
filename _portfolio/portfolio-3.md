---
title: "Multiview Clustering"
excerpt: ""
collection: portfolio
---

Many real datasets can be described as multiview in that they are comprised of multiple information sources on a common set of entities. Multiview clustering is the task of deriving *clusters* based on each source (or view). In Bayesian inference, this involves inferring several random partitions from the data. Since the views are assumed to be dependent, we would expect the partitions to be dependent as well. However, the complexities of the partition space make this problem nontrivial.

We address multiview clustering in ["Product Centered Dirichlet Processes for Bayesian Multiview Clustering"](https://arxiv.org/abs/2312.05365).  In that article, we propose CLusteirng with Independence Centering (CLIC), a Bayesian method for modeling dependent partitions. First, we simulate two sparse independent *root partitions*, then generate statistically dependent random partitions by perturbing the roots. CLIC is induced by the product centered Dirichlet process (PCDP), a simple but novel prior for the mixing measure. We show that CLIC and the PCDP satisfy appealing theoretic properties and derive a Gibbs sampler for inferring the posterior distribution of the dependent partitions. 
