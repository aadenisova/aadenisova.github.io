---
layout: page
title: "Projects"
lang: en
---

## Research Projects

{% for project in site.projects %}
  {% if project.lang == 'en' %}
- **[{{ project.title }}]({{ project.url }})** - {{ project.date | date: "%B %Y" }}
  {% endif %}
{% endfor %}
