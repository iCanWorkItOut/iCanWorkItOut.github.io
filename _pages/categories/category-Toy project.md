---
title: "Coding"
permalink: /categories/toy-project
layout: category
sidebar_main: true
---

about Toy Project
{% assign posts = site.categories.['Toy project'] %}
{% for post in posts %} {% include archive-custom.html type=page.entries_layout %} {% endfor %}
