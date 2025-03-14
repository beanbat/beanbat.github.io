---
layout: default
title: My public gis
---

# Some kewl projects :
{% for repo in site.github.public_repositories %}
- [{{ repo.name }}]({{ repo.html_url }})
{% endfor %}
