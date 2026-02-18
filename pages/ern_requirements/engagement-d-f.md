---
title: Stakeholder Engagement (D-F)
layout: page
sidebar: main
permalink: /engagement-d-f
---

This page shows each stakeholder engagement in the Research Notebooks project.

{% for plot in site.data.stakeholder-mapplots %}
  {% assign first = plot | slice: 0, 1 %}
  {% if first == "D" or first == "E" or first == "F" %}

## {{ plot }}

<iframe src="/research-notebooks-dev/assets/stakeholder-mapplots/{{ plot }}.html"
  width="100%" height="500" style="border:none;"></iframe>

---

  {% endif %}
{% endfor %}
