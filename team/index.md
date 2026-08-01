---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}

{% include section.html background="images/background.jpg" dark=true %}

Do you want to join the team? [Check openings.](research)

{% include section.html %}

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}


## Alumni

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'undergrad'" %}

{% include section.html background="images/background.jpg" dark=true %}

