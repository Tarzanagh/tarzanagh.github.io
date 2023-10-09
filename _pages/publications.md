---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


### Conference:

1. **Tarzanagh, Davoud Ataee**, Yingcong Li, Christos Thrampoulidis, and Samet Oymak. *Transformers as Support Vector Machines*. arXiv preprint arXiv:2308.16898 (2023).
2. **Tarzanagh, Davoud Ataee**, Mingchen Li, Pranay Sharma, and Samet Oymak. *Federated Multi-Sequence Stochastic Approximation with Local Hypergradient Estimation.* arXiv preprint arXiv:2306.01648 (2023).
3. **Tarzanagh, Davoud Ataee**, and Laura Balzano. *Online bilevel optimization: Regret analysis of online alternating gradient methods*. arXiv preprint arXiv:2207.02829 (2022).
4. **Tarzanagh, Davoud Ataee**, Laura Balzano, and Alfred O. Hero. *Fair Structure Learning in Heterogeneous Graphical Models*. arXiv preprint arXiv:2112.05128 (2021).
5. Sattar, Yahya, Zhe Du, **Davoud Ataee Tarzanagh**, Laura Balzano, Necmiye Ozay, and Samet Oymak. *Identification and adaptive control of markov jump systems: Sample complexity and regret bounds*. arXiv preprint arXiv:2111.07018 (2021).
6. Nazari, Parvin, **Davoud Ataee Tarzanagh**, and George Michailidis. *Adaptive First-and Zeroth-Order Methods for Weakly Convex Stochastic Optimization Problems* (2021).
7. WHager, William W., and **Davoud Ataee Tarzanagh**. *A Newton-Type Active Set Method for Nonlinear Optimization with Polyhedral Constraints* (2020).

