---
layout: page
title: "Поэзия"
lang: ru
---

## Стихи

{% for poem in site.poems %}
  {% if poem.lang == 'en' %}
- **[{{ poem.title }}]({{ poem.url }})** - {{ poem.date | date: "%B %Y" }}
  {% endif %}
{% endfor %}