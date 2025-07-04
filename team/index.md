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

## Lab Research Coordinators
{% include section.html %}
{% include list.html data="members" component="portrait" filters="role: manager" %}
{% include section.html %}

## Ferkauf Doctoral Students 
{% include section.html %}
{% include list.html data="members" component="portrait" filters="role: doctoral" %}
{% include section.html %}

## Collaborating Research Assistants 
{% include list.html data="members" component="portrait" filters="role: RA" %}
{% include section.html background="images/background.jpg" dark=true %}
{% include section.html %}

## Previous Research Coordinators
{% include list.html data="members" component="portrait" filters="role: prev-RC" %}
{% include section.html background="images/background.jpg" dark=true %}
{% include section.html %}

## Lab Alumni
{% include list.html data="members" component="portrait" filters="role: alum" %}
{% include section.html background="images/background.jpg" dark=true %}
{% include section.html %}

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}
