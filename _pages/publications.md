---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

2023
======
Algorithms and Complexity for Computing Nash Equilibria in Adversarial Team Games (with Ioannis Anagnostides, Fivos Kalogiannis, Manolis Vlatakis and Stephen McAleer).
EC 2023 [Arxiv]


2022
======

2021
======

2020
======

2019
======

2018
======

2017
======

2016
======

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
