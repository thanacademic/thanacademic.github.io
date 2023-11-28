---
layout: page
permalink: /publications/
title: Publications
description:
years: [2024, 2023, 2022, 2021, 2020, 2019, 2018, 2017]
nav: true
nav_order: 1
---

Full list: [[Google scholar](https://scholar.google.com/citations?user=Qtvu5t4AAAAJ&hl=en)] | [[DBLP](https://dblp.org/pid/65/4065-1.html)]
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}


</div>
