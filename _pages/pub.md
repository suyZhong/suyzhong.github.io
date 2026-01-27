---
layout: page
title: Publications
permalink: /publications/
description: 
nav: true
nav_order: 2
years: [2025, 2026]
# display_categories: [life]
# horizontal: false
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>