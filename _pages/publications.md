---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

2023
======
* [<em>Semi Bandit dynamics in Congestion Games: Convergence to Nash Equilibrium and No-Regret Guarantees</em>](https://sskoul.github.io/files/paper1.pdf)

        Ioannis Panageas, Luca Viano, Xiao Wang and Volkan Cevher, ICML 2023 (oral).

* [<em>STay-ON-the-Ridge: Guaranteed Convergence to Local Minimax Equilibrium in Nonconvex-Nonconcave Games</em>](https://sskoul.github.io/files/paper1.pdf) (COLT 2023)
  * joint work with Costis Daskalakis, Noah Golowich and Manolis Zampetakis.

* [<em>Min-Max Optimization Made Simple: Approximating the Proximal Point Method via Contraction Maps</\em>](https://sskoul.github.io/files/paper1.pdf) (SOSA 2023)
  * joint work with Volkan Cevher, George Piliouras and Ryan Simm.

2022
======
* [<em>Adaptive Stochastic Variance Reduction for Non-convex Finite-Sum Minimization</em>](https://sskoul.github.io/files/paper1.pdf) (NeurIPS 2022)
  * joint work with 	Ali Kavis, Kimon Antonakopoulos, Leello Tadesse Dadi and Volkan Cevher.

* [<em>Beyond Time-Average Convergence: Near-Optimal Uncoupled Online Learning via Clairvoyant Multiplicative Weights Update</em>](https://sskoul.github.io/files/paper1.pdf) (NeurIPS 2022)
  * joint work with Volkan Cevher, George Piliouras and Ryan Simm.

* [<em>Fast Convergence of Optimistic Gradient Ascent in Network Zero-Sum Extensive Form Games.</\em>](https://sskoul.github.io/files/paper1.pdf) (SAGT 2022)
  * joint work with George Piliouras, Lillian Ratliff and Ryan Simm.

2021
======

* [<em>The complexity of constrained min-max optimization./em>](https://sskoul.github.io/files/paper1.pdf) (STOC 2021)
  * joint work with Constantinos Daskalakis and Manolis Zampetakis.

* [<em>On the Approximability of Multistage Min-Sum Set Cover.</em>](https://sskoul.github.io/files/paper1.pdf) (ICALP 2021)
  * joint work with Dimitris Fotakis, Panagiotis Kostopanagiotis, Vasileios Nakos, Georgios Piliouras, Stratis Skoulakis.

* [<em>Efficient Online Learning for Dynamic k-Clustering.</\em>](https://sskoul.github.io/files/paper1.pdf) (SAGT 2022)
  * joint work with Dimitris Fotakis, Georgios Piliouras, Stratis Skoulakis.

* [<em>Online Learning in Periodic Zero-Sum Games.</\em>](https://sskoul.github.io/files/paper1.pdf) (NeurIPS 2022)
    * joint work with Tanner Fiez, Ryann Sim, Georgios Piliouras and Lillian Ratliff.

* [<em>Estimating the Number of Induced Subgraphs from Incomplete Data and Neighborhood Queries.</\em>](https://sskoul.github.io/files/paper1.pdf) (AAAI 2021)
    * joint work with Dimitris Fotakis, Thanasis Pittas, Stratis Skoulakis.

* [<em>Evolutionary Game Theory Squared: Evolving Agents in Endogenously Evolving Zero-Sum Games.</\em>](https://sskoul.github.io/files/paper1.pdf) (AAAI 2021)
      * joint work with Tanner Fiez, Ryann Sim, Georgios Piliouras and Lillian J. Ratliff.

* [<em>Evolutionary Game Theory Squared: Evolving Agents in Endogenously Evolving Zero-Sum Games.</\em>](https://sskoul.github.io/files/paper1.pdf) (AAAI 2021)
      * joint work with Tanner Fiez, Ryann Sim, Georgios Piliouras and Lillian J. Ratliff.

* [<em>Dynamical analysis of the EIP-1559 Ethereum fee market.</\em>](https://sskoul.github.io/files/paper1.pdf) (AFT 2021)
      * joint work with Stefanos Leonardos, Barnabé Monnot, Daniël Reijsbergen and Georgios Piliouras.

* [<em>Transaction Fees on a Honeymoon: Ethereum's EIP-1559 One Month Later.</\em>](https://sskoul.github.io/files/paper1.pdf) (Blockchain 2021)
        * joint work with Daniël Reijsbergen, Shyam Sridhar, Barnabé Monnot, Stefanos Leonardos and Georgios Piliouras.

2020
======

* [<em>Efficient Online Learning of Optimal Rankings: Dimensionality Reduction via Gradient Descent.</\em>](https://sskoul.github.io/files/paper1.pdf) (NeurIPS 2020)
        * joint work with Dimitris Fotakis, Thanasis Lianeas and Georgios Piliouras.

* [<em>The Online Min-Sum Set Cover Problem.</\em>](https://sskoul.github.io/files/paper1.pdf) (ICALP 2021)
      * joint work with Dimitris Fotakis, Loukas Kavouras, Grigorios Koumoutsos and Manolis Vardas.

* [<em>Node-Max-Cut and the Complexity of Equilibrium in Linear Weighted Congestion Games.</\em>](https://sskoul.github.io/files/paper1.pdf) (ICALP 2021)
      * joint work with Dimitris Fotakis, Anthimos Vardis Kandiros, Thanasis Lianeas, Nikos Mouzakis, Panagiotis Patsilinakos.


2019
======


* [<em>Opinion Formation Games with Aggregation and Negative Influence.</\em>](https://sskoul.github.io/files/paper1.pdf) (Theory Comput. Syst. 2019)
        * joint work with Markos Epitropou, Dimitris Fotakis and Martin Hoefer.

* [<em>Reallocating Multiple Facilities on the Line.</\em>](https://sskoul.github.io/files/paper1.pdf) (ICALP 2021)
      * joint work with Dimitris Fotakis, Loukas Kavouras, Panagiotis Kostopanagiotis, Philip Lazos and Nikos Zarifis.


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
