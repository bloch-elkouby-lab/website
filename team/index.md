---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team
{% include section.html %}
{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include section.html %}

## Clinical Research Coordinators
{% include section.html %}
{% include list.html data="members" component="portrait" filters="role: coord" %}
{% include section.html %}


## Ferkauf Doctoral Students 
{% include section.html %}
{% include list.html data="members" component="portrait" filters="role: fer_PhD" %}
{% include section.html %}

## Ferkauf Research Assistants
{% include section.html %}
{% include list.html data="members" component="portrait" filters="role: fer_MA" %}
{% include section.html %}

## Collaborating Research Assistants 
{% include list.html data="members" component="portrait" filters="role: other" %}
{% include section.html background="images/background.jpg" dark=true %}
{% include section.html %}

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}
