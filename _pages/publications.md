---
layout: page
permalink: /publications/
title: Publications
description:
years: [2024,2023,2022,2021]
nav: true
nav_order: 2
redirect: https://scholar.google.com/citations?user=RKLRsH0AAAAJ&hl=en
---

For the full paper list (including pre-prints), please see <ins>[Google Scholar](https://scholar.google.com/citations?user=RKLRsH0AAAAJ&hl=en)</ins>.

<!-- _pages/publications.md -->
<div class="publications">

{% for y in page.years %}
  <!--<h2 class="year">{{y}}</h2>-->
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
