---
title: Southern Ocean Dynamics and Marine Protected Areas
description: Using ocean models to inform ecosystem management.
image: images/Fig_homepage_MPAs.png
group: general
link: "https://cara-nissen.github.io/Nissen-lab-website/research_focus/general_theme3.html"
tags:
  - Southern Ocean
---

Some text.

Some text. 

Some text. 

Some text.

Some text.

## Selected Publications: Southern Ocean Dynamics

{% capture content %}
  {% include list.html data="citations" component="citation" filter="id == 'doi:10.67382/nczr5212'" style="small" %}
  {% include list.html data="citations" component="citation" filter="id == 'doi:10.1038/s41558-026-02561-9'" style="small" %}
  {% include list.html data="citations" component="citation" filter="id == 'doi:10.5194/os-20-85-2024'" style="small" %}
  {% include list.html data="citations" component="citation" filter="id == 'doi:10.1038/s41467-023-44438-x'" style="small" %}
  {% include list.html data="citations" component="citation" filter="id == 'doi:10.1175/jcli-d-22-0926.1'" style="small" %}
  {% include list.html data="citations" component="citation" filter="id == 'doi:10.1038/s41467-022-30671-3'" style="small" %}
{% endcapture %}

{%
  include grid.html
  content=content
  style="square"
%}

## Selected Publications: Marine Protected Areas

{% capture content %}
  {% include list.html data="citations" component="citation" filter="id == 'doi:10.3389/fmars.2026.1886905'" style="small" %}
  {% include list.html data="citations" component="citation" filter="id == 'doi:10.1038/s41467-026-69011-0'" style="small" %}
  {% include list.html data="citations" component="citation" filter="id == 'doi:10.1038/s41467-023-44438-x'" style="small" %}
  {% include list.html data="citations" component="citation" filter="id == 'doi:10.1111/conl.13053'" style="small" %} 
{% endcapture %}

{%
  include grid.html
  content=content
  style="square"
%}



