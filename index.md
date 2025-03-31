# 🚀 My GitHub Pages

Welcome to my GitHub Pages homepage! Here are my public projects that have their own GitHub Pages:

## 🌍 My Projects:
{% for repo in site.github.public_repositories %}
{% assign page_url = "https://" | append: site.github.owner_name | append: ".github.io/" | append: repo.name %}
- [{{ repo.name }}]({{ page_url }}) 🚀
{% endfor %}
