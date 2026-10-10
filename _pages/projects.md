---
title: "Projects"
permalink: /projects/
excerpt: "Data, BI and business projects."
---

A record of the projects I have worked on, from internship analyses to academic research.

{% assign projects = site.projects | sort: "order" %}
{% for post in projects %}
  {% include archive-single.html %}
{% endfor %}
