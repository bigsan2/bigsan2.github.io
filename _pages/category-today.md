---
title: "일상"
layout: archive
permalink: /today
toc: true
toc_sticky: true
toc_label: "MYSELF"
sidebar:
  nav: "sidebar-category"
---

{% assign posts = site.categories.today %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
