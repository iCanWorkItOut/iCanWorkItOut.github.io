---
title: "HTML/XML"
permalink: /categories/markup_language
layout: category
sidebar_main: true
---

Markup Language
{% assign posts = site.categories.['HTML/XML'] %}
{% for post in posts %} {% include archive-custom.html type=page.entries_layout %} {% endfor %}
