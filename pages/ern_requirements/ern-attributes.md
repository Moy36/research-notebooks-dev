---
title: ERN Attribute Definition
layout: page
sidebar: main
permalink: /ern-attributes
---

This page lists the attribute definitions used in the Research Notebooks project.

## Main FRs Score Plot
<iframe src="https://oiseau-lab.github.io/research-notebooks-dev/plots/anteater" width="100%" height="600" style="border:none;"> </iframe>

## Attribute List


<table>
  {% for row in site.data.ERNAttributeDefinition %}
    {% if forloop.first %}
    <tr>
      {% for pair in row %}
        <th>{{ pair[0] }}</th>
      {% endfor %}
    </tr>
    {% endif %}

    {% tablerow pair in row %}
      {{ pair[1] }}
    {% endtablerow %}
  {% endfor %}
</table>
