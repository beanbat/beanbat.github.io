---
layout: default
title: My GitHub Pages
---

## 🚀 My Projects Hosted on GitHub Pages:

{% for repo in site.github.public_repositories %}
{% assign page_url = "https://" | append: site.github.owner_name | append: ".github.io/" | append: repo.name %}
- [{{ repo.name }}]({{ page_url }}) 🚀
{% endfor %}
