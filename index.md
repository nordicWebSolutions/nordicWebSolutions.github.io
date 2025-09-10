---
layout: default
title: Willkommen
---

# Kleine Firma, smarte Lösungen

Einblicke in unseren Alltag als kleine Softwarefirma – mit pragmatischen Ideen, echten Projekten und smarten Lösungen für kleine Unternehmen.

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%d.%m.%Y" }}
{% endfor %}

[Alle Beiträge anzeigen](/posts.html)
