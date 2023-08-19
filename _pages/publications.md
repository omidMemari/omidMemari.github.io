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




**Superhuman Fairness**

Omid Memarrast, Linh Vu, Brian D. Ziebart.

In International Conference on Machine Learning, pp. 24420-24435. PMLR, 2023.