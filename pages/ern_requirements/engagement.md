---
title: Stakeholder Engagements
layout: page
sidebar: main
permalink: /engagement
---

This page shows each stakeholder engagement in the Research Notebooks project.

{% for plot in site.data.stakeholder-mapplots %}
  {% assign first = plot | slice: 0 | downcase %}
  {% if first == "a" or first == "b" %}

## {{ plot }}

<iframe 
    src="/research-notebooks-dev/assets/stakeholder-mapplots/{{ plot }}.html"
    width="100%"
    height="500"
    style="border:none;">
</iframe>

  {% endif %}
{% endfor %}




