---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Meet the team!

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}

{% include section.html background="images/background.jpg" dark=true %}

Do you want to join the team? [Check openings.](https://cara-nissen.github.io/Nissen-lab-website/openings/)

{% include section.html %}

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}


## Alumni

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'undergrad'" %}

{% include section.html background="images/background.jpg" dark=true %}

