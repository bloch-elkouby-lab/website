---
title: Team
nav:
  order: 2
  tooltip: Our Team
---

# {% include icon.html icon="fa-solid fa-users" %}Team
{% include section.html %}
{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include section.html %}

## Ferkauf Research Assistants
{% include section.html %}
{% include list.html data="members" component="portrait" filters="role: TA" %}
{% include section.html %}

## Ferkauf Doctoral Students 
{% include section.html %}
{% include list.html data="members" component="portrait" filters="role: fer_PhD" %}
{% include section.html %}

## Collaborating Research Assistants 
{% include list.html data="members" component="portrait" filters="role: other" %}
{% include section.html background="images/background.jpg" dark=true %}
{% include section.html %}

## Lab Alumni
{% include list.html data="members" component="portrait" filters="role: alum" %}
{% include section.html background="images/background.jpg" dark=true %}
{% include section.html %}

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}
