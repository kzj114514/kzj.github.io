---
title: "Archive Layout with Content"
layout: archive
permalink: /archive-layout-with-content/
---

A variety of common markup showing how the theme styles them.


{% include base_path %}
{% for post in site.pages %}
{% include archive-single.html %}
{% endfor %}
