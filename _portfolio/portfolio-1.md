---
title: "Decision Theoretic Clustering"
excerpt: ""
collection: portfolio
---
Using Bayesian mixture models for cluster analysis is highly sensitive to model misspecification, typically resulting in more clusters than are actually present in the data. In ["Bayesian Clustering via Fusing of Localized Densities"](https://arxiv.org/abs/2304.00074), we propose to extricate components from clusters, instead characterizing clusters with multiple components via Fusing of Localized Densities (FOLD). Our method has has a fully decision theoretic justification, can be easily implemented as an add-on to a Bayesian procedure, and leads to appealing properties in the large sample limit. FOLD can be implemented in practice using the ```foldcluster``` package, which is available on [Github](https://github.com/adombowsky/FOLD).
