---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Peer-reviewed publications

Olympio Hacquard, Krishnakumar Balasubramanian, Gilles Blanchard, Clément Levrard and Wolfgang Polonik. **Topologically penalized regression on manifolds**. Journal of Machine Learning Research, 23(161):1−39. [[PDF]](https://jmlr.org/papers/volume23/21-1270/21-1270.pdf). (2022).

## Preprints

* Olympio Hacquard and Vadim Lebovici. **Euler characteristic tools for topological data analysis**. arXiv:2303.14040. [[PDF]](https://arxiv.org/pdf/2303.14040.pdf) (2023).

* Olympio Hacquard, Gilles Blanchard and Clément Levrard. **Statistical learning on measures: an application to persistence diagrams**. arXiv:2303.08456. [[PDF]](https://arxiv.org/pdf/2303.08456.pdf) (2023).

* Patrick Cattiaux, Fanny Delebcque and Olympio Hacquard. **Topological interactions for collective dynamics: a study of a (not so) simple model**. [[PDF]](https://perso.math.univ-toulouse.fr/cattiaux/files/2013/11/topologic-rev1.pdf) (2019).

## Other

Olympio Hacquard, Etienne Lasalle, Vadim Lebovici. **Challenge Mathematics-Enterprise (1st place). Pedestrians trajectory reconstruction, Eurecam company**. [[PDF]](https://hal.science/hal-03345714v1/document) (2021).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
