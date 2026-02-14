---
title: Stakeholder Engagements
layout: page
sidebar: main
permalink: /engagement
---

This page shows each stakeholder engagement in the Research Notebooks project.

{% assign filtered = site.data.stakeholder-mapplots | where_exp: "p", "p[0] == 'A' or p[0] == 'B'" %}

{% for plot in filtered %}

## {{ plot }}

<iframe src="/research-notebooks-dev/assets/stakeholder-mapplots/{{ plot }}.html"
  width="100%" height="500" style="border:none;"></iframe>

---

{% endfor %}





