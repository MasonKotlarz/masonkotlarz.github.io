---
layout: page
title: "Projects"
permalink: /projects/
---

# My Projects

Below are a few projects that highlight my skills and interests:

{% for project in site.projects %}
## [{{ project.title }}]({{ project.url }})
{{ project.summary }}

**Role:** {{ project.role }}  
**Skills:** {{ project.skills | join: ", " }}

---

{% endfor %}

