---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## PhD Manuscript

Olympio Hacquard. **From topological features to machine learning models: a journey through persistence diagrams**. [[PDF]](https://theses.hal.science/tel-04328645v1/document)  (2023)

## Peer-reviewed publications

* Olympio Hacquard, Krishnakumar Balasubramanian, Gilles Blanchard, Clément Levrard and Wolfgang Polonik. **Topologically penalized regression on manifolds**. Journal of Machine Learning Research, 23(161):1−39. [[PDF]](https://jmlr.org/papers/volume23/21-1270/21-1270.pdf). (2022).

* Patrick Cattiaux, Fanny Delebcque and Olympio Hacquard. **Some flocking properties for a model of collective dynamics with topological interactions**. Communications in Mathematical Sciences [[PDF]](https://perso.math.univ-toulouse.fr/cattiaux/files/2013/11/topologic-rev1.pdf) (2024).

* Olympio Hacquard and Vadim Lebovici. **Euler characteristic tools for topological data analysis**. Journal of Machine Learning Research 25(240):1−39, 2024. [[PDF]](https://www.jmlr.org/papers/volume25/23-0353/23-0353.pdf) (2024).

* Michael Etienne Van Huffel, Olympio Hacquard, Vadim Lebovici, Matteo Palo. **Discrete transforms of quantized persistence diagrams**. ALENEX 25. [[PDF]](https://arxiv.org/pdf/2303.14040) (2024).

* Olympio Hacquard. **Hypergraph clusering using Ricci curvature: an edge transport perspective**. To appear in Transactions of Machine Learning [[PDF]](https://arxiv.org/pdf/2412.15695) (2025).

* Olympio Hacquard, Gilles Blanchard and Clément Levrard. **Statistical learning on measures: an application to persistence diagrams**. To appear in Electronic Journal of Statistics [[PDF]](https://hal.science/hal-04028783v3/document) (2026).



## Other

Olympio Hacquard, Etienne Lasalle, Vadim Lebovici. **Challenge Mathematics-Enterprise (1st place). Pedestrians trajectory reconstruction, Eurecam company**. [[PDF]](https://hal.science/hal-03345714v1/document) (2021).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
