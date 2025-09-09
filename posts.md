---
layout: default
title: Alle Beiträge
permalink: /posts/
---

# Alle Beiträge

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%d.%m.%Y" }}
  {{ post.excerpt }}
{% endfor %}
