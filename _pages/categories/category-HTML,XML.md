---
title: "HTML/XML"
permalink: /categories/html-xml
layout: category
sidebar_main: true
---

Markup Language
{% assign posts = site.categories.['HTML/XML'] %}
{% for post in posts %} {% include archive-custom.html type=page.entries_layout %} {% endfor %}
