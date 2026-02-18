---
title: ERN Attribute Overview
layout: page
sidebar: main
permalink: /ern-attributes
---

This page lists the attribute definitions used in the Research Notebooks project.

## Main FRs Score Plot
<iframe 
    src="/research-notebooks-dev/assets/functional-requirements.html"
    width="100%"
    height="600"
    style="border:none;">
</iframe>

## Attribute Table


<table class="attr-table">
  <colgroup>
    <col style="width: 15%;">
    <col style="width: 25%;">
    <col style="width: 60%;">
  </colgroup>

  {% for row in site.data.ERNAttributeDefinitionNew %}
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

