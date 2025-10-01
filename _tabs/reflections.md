---
layout: page
title: Reflections
permalink: /reflections/
icon: fas fa-book
order: 5
---
{% for reflection in site.reflections %}
- [{{ reflection.title }}]({{ reflection.url }})
{% endfor %}
