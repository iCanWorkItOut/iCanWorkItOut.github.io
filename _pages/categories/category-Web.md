---
title: "Front-End"
permalink: /categories/web
layout: category
sidebar_main: true
---

{% assign posts = site.categories.Web %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}