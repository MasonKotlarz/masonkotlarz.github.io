---
layout: page
title: Internship Experience
permalink: /experience/
icon: fas fa-briefcase
order: 4
---
{% for exp in site.experience %}
- [{{ exp.title }}]({{ exp.url }})
{% endfor %}
