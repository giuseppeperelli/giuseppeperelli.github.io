---
layout: page
title: Publications
permalink: /publications/
description:
years: [2025,2024,2023,2022,2021,2020,2019,2018,2017,2016,2015,2014,2012]
nav: true
nav_order: 3
---
<div class="publications">

Most of the papers available from this list appear in print, and the corresponding copyright is held by the publisher. While the papers can be used for personal use, redistribution or reprinting for commercial purposes is prohibited. Preproceedings versions are available upon request.

{%- for y in page.years %}
<!--   <h2 class="year">{{y}}</h2> -->
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>


