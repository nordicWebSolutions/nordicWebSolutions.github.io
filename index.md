---
layout: default
title: Willkommen
---

# Willkommen auf meinem Blog!

Hier schreibe ich über [dein Thema]. Schau dir meine neuesten Beiträge an:

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%d.%m.%Y" }}
{% endfor %}

[Alle Beiträge anzeigen](/posts.html)
