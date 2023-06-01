---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

2023
======
* <em>Semi Bandit dynamics in Congestion Games: Convergence to Nash Equilibrium and No-Regret Guarantees</em> (ICML 2023 oral)
  * joint work with Ioannis Panageas, Luca Viano, Xiao Wang and Volkan Cevher.

* STay-ON-the-Ridge: Guaranteed Convergence to Local Minimax Equilibrium in Nonconvex-Nonconcave Games (COLT 2023)
  * joint work with Costis Daskalakis, Noah Golowich and Manolis Zampetakis.

* Min-Max Optimization Made Simple: Approximating the Proximal Point Method via Contraction Maps (SOSA 2023)
  * joint work with Volkan Cevher, George Piliouras and Ryan Simm.

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
