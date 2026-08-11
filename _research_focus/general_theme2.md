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

Our understanding of the physical, chemical, and biological dynamics of the ocean has benefitted tremendously from improved observing technologies and increased spatial and temporal coverage. Despite these advances, one challenge associated with real-world observations is that these provide a snapshot view of the ocean state, making it difficult to know how representative any observation is for longer temporal or larger spatial scales. In addition, observation-derived products, sometimes merging observations from different technologies or sensors, are affected by sampling inaccuracies and incomplete spatio-temporal coverage, which complicates the robust detection of change in ocean properties and fluxes, including biological productivity or air-sea CO2 fluxes. 

Ocean models can support the design of improved observing networks. This is because in the model world, we have complete knowledge of ocean properties and fluxes at all locations and at all times. **Our group aims to enhance the utility of synthetic observing systems in ocean models to enhance the interpretation of observational records and support observing system design.** To achieve that, our group (co-)develops the implementation of and uses observing systems implemented directly into ocean models (e.g., floats, satellites). Extracting synthetic observations during model run time, this approach is unique in that it gives us the same snapshot view of the modeled ocean that real-world observations give us of the real ocean. Comparison with the true model fields then helps isolating the most critical sources of uncertainty in our current ocean observing systems.

## Selected Publications

{% capture content %}
  {% include list.html data="citations" component="citation" filter="id == 'doi:10.5194/egusphere-2026-4623'" style="small" %}
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



