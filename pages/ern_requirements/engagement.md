---
title: Stakeholder Engagements
layout: page
sidebar: main
permalink: /engagement
---

This page lists the stakeholders' engagement for functional requirments in the Research Notebooks project.

{% for plot in site.data.plots %}
## {{ plot }}

<iframe 
    src="/research-notebooks-dev/assets/stakeholder-mapplots/{{ plot }}.html"
    width="100%"
    height="600"
    style="border:none;">
</iframe>

---
{% endfor %}
