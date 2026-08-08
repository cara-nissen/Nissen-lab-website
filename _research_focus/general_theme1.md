---
title: Marine Ecosystem Dynamics
description: Modeling the interactions between marine ecosystems and biogeochemical cycles.
image: images/Fig_homepage_ecosystems.png
group: general
link: "https://cara-nissen.github.io/Nissen-lab-website/research_focus/general_theme1.html"
tags:
  - Southern Ocean
  - Arctic
  - Global
---

Some text.

Some text. 

Some text. 

Some text.

Some text.

## Selected Publications

{% capture content %}
  {% include list.html data="citations" component="citation" filter="id == 'doi:10.1111/gcb.70063'" style="small" %}
  {% include list.html data="citations" component="citation" filter="id == 'doi:10.1029/2024GB008403'" style="small" %}
  {% include list.html data="citations" component="citation" filter="id == 'doi:10.1111/gcb.16799'" style="small" %}
  {% include list.html data="citations" component="citation" filter="id == 'doi:10.1029/2021gb006991'" style="small" %}
  {% include list.html data="citations" component="citation" filter="id == 'doi:10.5194/bg-18-251-2021'" style="small" %}
  {% include list.html data="citations" component="citation" filter="id == 'doi:10.5194/bg-15-6997-2018'" style="small" %}
{% endcapture %}

{%
  include grid.html
  content=content
  style="square"
%}

