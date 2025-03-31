> Beanbat

![beanbat](/files/beanbatGPT.png]

> One day I stepped on a slug, it was weird.

##  My Projects:
i{% for repo in site.github.public_repositories %}
{% assign page_url = "https://" | append: site.github.owner_name | append: ".github.io/" | append: repo.name %}
- [{{ repo.name }}]({{ page_url }}) 🚀
{% endfor %}
