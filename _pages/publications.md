---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Journals

**Dombowsky, A.**, Dunson, D. B., Madut, D. B., Rubach, M. P., and Herring,  A. H. (2025). Bayesian learning of clinically meaningful sepsis phenotypes in northern Tanzania. *The Annals of Applied Statistics*. [[Publication](https://projecteuclid.org/journals/annals-of-applied-statistics/volume-19/issue-3/Bayesian-learning-of-clinically-meaningful-sepsis-phenotypes-in-northern-Tanzania/10.1214/25-AOAS2045.short)] [[Preprint](https://arxiv.org/abs/2405.01746)] [[Code](https://github.com/adombowsky/CLAMR)].

**Dombowsky, A.** and Dunson, D. B. (2025) Product centred Dirichlet processes for Bayesian multiview clustering. *Journal of the Royal Statistical Society, Series B*. [[Publication](https://academic.oup.com/jrsssb/advance-article/doi/10.1093/jrsssb/qkaf021/8123289)] [[Preprint](https://arxiv.org/abs/2312.05365)] [[Code](https://github.com/adombowsky/clic)].

**Dombowsky, A.** and Dunson, D. B. (2025) Bayesian clustering via fusing of localized densities. *Journal of the American Statistical Association: Theory and Methods.* [[Publication](https://www.tandfonline.com/doi/full/10.1080/01621459.2024.2427935)] [[Preprint](https://arxiv.org/abs/2304.00074)] [[Package](https://github.com/adombowsky/FOLD)]

## Submitted

**Dombowsky, A.** and Dunson, D. B. (2025+). Learning discrete Bayesian networks with hierarchical Dirichlet shrinkage. [[Preprint](https://arxiv.org/abs/2509.13267)] [[Code](https://github.com/adombowsky/HiDDeN_DAG)].

Madut, D. B., **Dombowsky, A.**, [& 16 others]. (2025+) Derivation of sepsis subtypes in northern Tanzania using Bayesian probabilistic clustering of clinical data.

## Ongoing Work

**Dombowsky, A.**, Engelhardt, B. E., and Ramdas, A. (2026). Besag-Clifford e-values for unnormalized testing.


Meng, J., **Dombowsky, A.**, and Dunson, D. B. (2025+). Kernel robust Bayesian clustering in high dimensions.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
