---
layout: page
title: "Reflections"
permalink: /reflections/
---

# 📚 My Reflections

Below are my key reflections during the CPRE program:

{% for reflection in site.reflections %}
## [{{ reflection.title }}]({{ reflection.url }})
{{ reflection.summary }}

---

{% endfor %}

