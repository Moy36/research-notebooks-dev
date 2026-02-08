---
title: Stakeholder Engagements
layout: page
sidebar: main
permalink: /engagement
---

{% for plot in site.data.stakeholder-mapplots %}
## {{ plot }} Contribution

<iframe 
    src="/research-notebooks-dev/assets/stakeholder-mapplots/{{ plot }}.html"
    width="100%"
    height="500"
    style="border:none;">
</iframe>

---
{% endfor %}

