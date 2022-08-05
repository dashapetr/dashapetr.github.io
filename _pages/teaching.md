---
layout: page
permalink: /teaching/
title: teaching
description:  A short summary of my teaching experience.
years: [2022, 2021]
nav: true
nav_order: 4
---
<!-- _pages/teaching.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f teachings -q @*[year={{y}}]* %}
{% endfor %}

</div>