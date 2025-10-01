---
layout: page
title: Projects
permalink: /projects/
icon: fas fa-project-diagram
order: 2
---
{% for project in site.projects %}
- [{{ project.title }}]({{ project.url }})
{% endfor %}
