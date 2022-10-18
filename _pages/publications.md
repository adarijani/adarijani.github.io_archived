---
layout: page
permalink: /useful papers/
title: useful papers
description: Impactfull papers that I found interesting.
years: [1998]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
