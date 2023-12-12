---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Preprints

Dombowsky, A. and Dunson, D. (2023+) [Product centered Dirichlet processes for dependent clustering](https://arxiv.org/abs/2312.05365). *Submitted.* 
* [GitHub Repo](https://github.com/adombowsky/clic).

Dombowsky, A. and Dunson, D. (2023+) [Bayesian clustering via fusing of localized denstities](https://arxiv.org/abs/2304.00074). *Submitted.* 
* [GitHub Repo](https://github.com/adombowsky/FOLD).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
