#---
layout: page
permalink: /publications/
title: readings
description: These publications are the ones that I enjoy most and learn from. 
years: [2023, 2021, 2020, 2017, 2016, 2015, 2014] 
nav: true
nav_order: 1
#---
#---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
#---