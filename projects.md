---
layout: page
title: "Projects"
permalink: /projects/
---

Here are my projects:

{% for project in site.projects %}
- [{{ project.title }}]({{ project.url }})
{% endfor %}
