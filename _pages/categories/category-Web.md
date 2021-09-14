---
title: "Front-End"
permalink: /categories/web
layout: category
sidebar_main: true
---

Web & Front-end
{% assign posts = site.categories.Web %}
{% for post in posts %} {% include archive-custom.html type=page.entries_layout %} {% endfor %}
