---
layout: page
permalink: /publications/
title: publications
description: selected publications in reverse chronological order
years: [2022, 2021, 2020, 2018, 2016, 2011, 2007, 2006]
nav: true
---
For a full list, please see my Google scholar [page](https://scholar.google.com/citations?user=bRc87BMAAAAJ&hl=en)

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
