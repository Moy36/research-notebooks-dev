---
title: Stakeholder Engagements
layout: page
sidebar: main
permalink: /engagementab
---

This page shows each stakeholder engagement in the Research Notebooks project.

{% for plot in site.data["stakeholder-mapplots"] %}
  {% assign first_letter = plot | slice: 0, 1 | downcase %}
  {% if first_letter == "a" or first_letter == "b" %}

## {{ plot }}

<iframe 
    src="/research-notebooks-dev/assets/stakeholder-mapplots/{{ plot }}.html"
    width="100%"
    height="500"
    style="border:none;">
</iframe>

---

  {% endif %}
{% endfor %}



