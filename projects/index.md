---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include tags.html tags="Southern Ocean, Arctic, Global" %}

{% include search-info.html %}

{% include section.html %}

## General themes

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## Funded projects

{% include list.html component="card" data="projects" filter="!group" style="small" %}
