---
layout: page
title: Publications
permalink: /publications/
years: [2025, 2024, 2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014, 2013]
---
<div class="publications">

  {%- for y in page.years %}
  <div class="year-container">
    <hr class="year-divider" />
    <h2 class="year">{{y}}</h2>
  </div>
  {% bibliography -q @*[year={{y}}]* %}
  {% endfor %}

</div>
