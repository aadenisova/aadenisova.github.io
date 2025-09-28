---
layout: page
title: "Проекты"
lang: ru
---

## Научные проекты

{% for project in site.projects %}
  {% if project.lang == 'en' %}
- **[{{ project.title }}]({{ project.url }})** - {{ project.date | date: "%B %Y" }}
  {% endif %}
{% endfor %}
