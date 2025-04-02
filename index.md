

Hello there
Here's all the mess

##  My Projects:
{% for repo in site.github.public_repositories %}
{% assign page_url = "https://" | append: site.github.owner_name | append: ".github.io/" | append: repo.name %}
- [{{ repo.name }}]({{ page_url }})
{% endfor %}

https://github.com/Naxyrius/tssr-linux-debian-post-install/settings