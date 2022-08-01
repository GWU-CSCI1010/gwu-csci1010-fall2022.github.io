---
title: Assignments
narrow: true
permalink: list/assignments.html
show_profile: true
---

{% for project in site.assignments %}
- [{{ project.title }}]({{ site.baseurl }}{{ project.url }})
{% endfor %}
