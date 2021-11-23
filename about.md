---
layout: default
title: poster
---

{% capture introduction %}

Does this work? It seems like it! 

{% endcapture %}

{% capture methods %}

what about this?
{{ site.data.abstract.methods.content }}

{% endcapture %}

{% capture results %}

and this?
{{ site.data.abstract.results.content }}

{% endcapture %}

{% capture conclusion %}

aaand this?
{{ site.data.abstract.conclusion.content }}

{% endcapture %}

{% include sections.html %}