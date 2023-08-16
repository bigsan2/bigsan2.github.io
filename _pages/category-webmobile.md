---
title: "Web/Mobile"
layout: archive
permalink: /webmobile
sidebar:
  nav: "sidebar-category"
---

{% assign posts = site.categories.webmobile %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
