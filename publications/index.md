---
layout: default
title: Publications
nav_order: 4
---

# Publications

Here is a collection of our published work, pre-prints, and collaborative research.

{% include section.html %}

{% capture search_controls %}
  {% include search-box.html id="search" placeholder="Search publications..." %}
{% endcapture %}
{% include controls-block.html left=search_controls %}

{% include list.html data="citations" component="citation" search_id="search" %}
