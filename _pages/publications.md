---
layout: page
permalink: /publications/
title: publications
years: [2022, 2021, 2020, 2018]
nav: true
---

A list of my publications. For a more comprehensive and accurate list, check my [Google Scholar](https://scholar.google.com/citations?user=GKJnjkgAAAAJ&hl=en).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
