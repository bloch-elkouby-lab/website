---
title: News & Events
nav:
  order: 7
  tooltip: news and upcoming events
---

# {% include icon.html icon="fa-solid fa-wrench" %}News & Upcoming Events

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

{% capture text %}
News text 1
{% endcapture %}

{%
  include feature.html
  image="images/ai_pic.jpg"
  link=""
  title="News title 1"
  flip=true
  style="bare"
  text=text
%}



{% capture text %}
News text 2
{% endcapture %}

{%
  include feature.html
  image="images/alliance.jpg"
  link=""
  title="news title 2"
  flip=false
  style="bare"
  text=text
%}

