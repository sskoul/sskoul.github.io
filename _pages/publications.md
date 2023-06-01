---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

2023
======
* Semi Bandit dynamics in Congestion Games: Convergence to Nash Equilibrium and No-Regret Guarantees (ICML 2023 oral)
  * joint work with Ioannis Panageas, Luca Viano, Xiao Wang and Volkan Cevher.
  * International Conference on Machine Learning, ICML 2023 (oral)

* STay-ON-the-Ridge: Guaranteed Convergence to Local Minimax Equilibrium in Nonconvex-Nonconcave Games
  * joint work with Costis Daskalakis, Noah Golowich and Manolis Zampetakis.
  * Colloquim on Learning Theory (COLT 2023)
* Min-Max Optimization Made Simple: Approximating the Proximal Point Method via Contraction Maps
  * joint work with Volkan Cevher, George Piliouras and Ryan Simm.
  * Symposium on the Simplicity of Algorithms (SOSA 2023)

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
