---
title: Stakeholder Engagement (S-W)
layout: page
sidebar: main
permalink: /engagement-s-w
---

This page shows each stakeholder engagement in the Research Notebooks project.

{% for plot in site.data.stakeholder-mapplots %}
  {% assign first = plot | slice: 0, 1 %}
  {% if first == "S" or first == "T" or first == "U" or first == "V" or first == "W" %}

## {{ plot }}

<iframe src="/research-notebooks-dev/assets/stakeholder-mapplots/{{ plot }}.html"
  width="100%" height="500" style="border:none;"></iframe>

---

  {% endif %}
{% endfor %}
