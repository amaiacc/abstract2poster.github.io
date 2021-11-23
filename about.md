---
layout: default
title: abstract
---
{% for item in site.data.abstract %}
  {% capture section %}
  {{ item }}
  {% endcapture %} 
{% endfor %}

{% include sections.html %}