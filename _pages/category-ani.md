---
title: "영화/애니"
layout: archive
permalink: /ani
toc: true
toc_sticky: true
toc_label: "MYSELF"
sidebar:
  nav: "sidebar-category"
---

{% assign posts = site.categories.ani %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
