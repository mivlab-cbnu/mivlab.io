---
title: News
nav:
  order: 5
  # tooltip: 
---

{% capture col1 %}

### {% include icon.html icon="fa-solid fa-newspaper" %}News

{% include list.html data="news" component="news" %}

{% endcapture %}

{% include cols.html col1=col1 %}
