---
title: "Web/Mobile"
layout: archive
permalink: /webmobile
toc: true
toc_sticky: true
toc_label: "MYSELF"
sidebar:
  nav: "sidebar-category"
---

{% assign posts = site.categories.webmobile %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
