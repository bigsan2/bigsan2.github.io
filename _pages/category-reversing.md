---
title: "Reversing"
layout: archive
permalink: /reversing
---

{% assign posts = site.categories.reversing %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
