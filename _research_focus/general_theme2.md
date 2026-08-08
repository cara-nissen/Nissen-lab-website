---
title: Observing System Design
description: Using synthetic observations from ocean models to inform sampling strategies.
image: images/Fig_homepage_observing_systems.png
group: general
link: "https://cara-nissen.github.io/Nissen-lab-website/research_focus/general_theme2.html"
tags:
  - Southern Ocean
  - Global
---

Some text.

Some text.

Some text.

Some text.


## Relevant Publications

{% capture content %}
  {% include list.html data="citations" component="citation" filter="id == 'doi:10.22541/essoar.15006783/v1'" style="small" %}
  {% include list.html data="citations" component="citation" filter="id == 'doi:10.1029/2025GB008550'" style="small" %}
  {% include list.html data="citations" component="citation" filter="id == 'doi:10.5194/gmd-17-6415-2024'" style="small" %}
   {% include list.html data="citations" component="citation" filter="id == 'doi:10.1098/rsta.2022.0063'" style="small" %}
{% endcapture %}

{%
  include grid.html
  content=content
  style="square"
%}



