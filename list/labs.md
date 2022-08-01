---
title: Labs & Lectures
permalink: list/labs.html
---
**Fall 2021 microLabs: [Python programming using DeepNote] & [Raspberry Pi exercises]**
<!--- Will be updated as the course progresses -->
{% for lab in site.labs %}
- [{{ lab.title }}]({{ site.baseurl }}{{ lab.url }})
{% endfor %}

**Archived Fall 2020 microLabs: [Python programming using Jupyter] & [App building using Thunkable]**

{% for lab in site.fall2020_labs %}
- [{{ lab.title }}]({{ site.baseurl }}{{ lab.url }})
{% endfor %}
