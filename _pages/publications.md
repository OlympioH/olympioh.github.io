---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Peer-reviewed publications


## Preprints

Olympio Hacquard and Vadim Lebovici. Euler characteristic tools for topolog-
ical data analysis. arXiv preprint [arXiv:2303.14040](https://arxiv.org/pdf/2303.14040.pdf), 2023.

## Other


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
