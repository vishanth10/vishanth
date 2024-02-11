---
layout: page
permalink: /publications/
title: Publications
description: Conference Publications and Thesis Reports
years: [2022, 2021]
nav: false
nav_order: 6
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
