---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Journals

**Dombowsky, A.**, Dunson, D. B., Madut, D. B., Rubach, M. P., and Herring,  A. H. (2025). Bayesian learning of clinically meaningful sepsis phenotypes in northern Tanzania. *The Annals of Applied Statistics*. In press.
* [ArXiv Preprint](https://arxiv.org/abs/2405.01746)
* [Github Repo](https://github.com/adombowsky/CLAMR)

**Dombowsky, A.** and Dunson, D. B. (2025) [Product centred Dirichlet processes for Bayesian multiview clustering](https://academic.oup.com/jrsssb/advance-article/doi/10.1093/jrsssb/qkaf021/8123289). *Journal of the Royal Statistical Society, Series B*. In press.
* [ArXiv Preprint](https://arxiv.org/abs/2312.05365)
* [Github Repo](https://github.com/adombowsky/clic)

**Dombowsky, A.** and Dunson, D. B. (2024) [Bayesian clustering via fusing of localized densities](https://www.tandfonline.com/doi/full/10.1080/01621459.2024.2427935). *Journal of the American Statistical Association: Theory and Methods.* In press.
* [ArXiv Preprint](https://arxiv.org/abs/2304.00074).
* [Github Repo and R Package](https://github.com/adombowsky/FOLD)

## Submitted
Madut, D. B., **Dombowsky, A.**, [& 16 others]. (2025+) Derivation of sepsis subtypes in northern Tanzania using Bayesian probabilistic clustering of clinical data.

## Ongoing Work
**Dombowsky, A.** and Dunson, D. B. (2025+). Hierarchical directed Dirichlet networks for discrete graphical modeling. *Working Paper*.

Meng, J., **Dombowsky, A.**, and Dunson, D. B. (2025+). Kernel robust Bayesian clustering in high dimensions. *Working Paper*.



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
