---
layout: default 
title: "Blogs"
---

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Blogs" %}
{% endif %}