---
layout: list
title:  Archive
---

### List of categories:
{% for category in site.featured_categories %}
* [ {{ category.title }} ]({{ category.url }})
{% endfor %}

### List of tags:
{% for tag in site.featured_tags %}
* [ {{ tag.title }} ]({{ tag.url }})
{% endfor %}