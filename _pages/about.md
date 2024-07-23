---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a second year PhD student at the University of British Columbia (UBC) under the supervision of [Giuseppe Carenini](https://www.cs.ubc.ca/~carenini/) and [Gabriel Murray](https://gabrielmurray.ca/).
My research spans various areas of Natural Language Processing (NLP), including on model interpretability, incorporating linguistic structures, topic modeling, visualization, etc.
Prior to joining the [UBC NLP Group](https://nlp.cs.ubc.ca/), I was undergraduate student at the University of Toronto, where I completed the Computer Science Specialist Program while minoring in Math.

Selected Publications
======
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find the full list of my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}