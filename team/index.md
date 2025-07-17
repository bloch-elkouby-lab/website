---
title: Team
nav:
  order: 2
  tooltip: Team
---

# {% include icon.html icon="fa-solid fa-users" %}Team
{% include section.html %}
{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include section.html %}

## Lab Manager and Research Coordinators
{% include section.html %}
{% include list.html data="members" component="portrait" filters="role: manager" %}
{% include section.html %}

## Ferkauf Doctoral Students 
{% include section.html %}
{% include list.html data="members" component="portrait" filters="role: doctoral" %}
{% include section.html %}

## Collaborating Research Assistants 
{% include section.html %}
{% include list.html data="members" component="portrait" filters="role: RA" %}
{% include section.html %}

## Previous Coordinators
{% include section.html %}
{% include list.html data="members" component="portrait" filters="role: prev-RC" %}
{% include section.html %}

## Lab Alumni
{% include section.html %}
{% include list.html data="members" component="portrait" filters="role: alum" %}
{% include section.html %}

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}
