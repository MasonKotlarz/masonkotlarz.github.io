---
layout: page
title: Reflections
permalink: /reflections/
icon: fas fa-book
order: 3
---
{% for reflection in site.reflections %}
- [{{ reflection.title }}]({{ reflection.url }})
{% endfor %}
