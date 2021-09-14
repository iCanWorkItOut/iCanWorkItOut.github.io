---
title: "GitHub Pages"
permalink: /categories/blog
layout: category
sidebar_main: true
---

Jekyll & minimal-mistakes
{% assign posts = site.categories.Blog %}
{% for post in posts %} {% include archive-custom.html type=page.entries_layout %} {% endfor %}
