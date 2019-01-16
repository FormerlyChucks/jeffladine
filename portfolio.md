---
title: Adam LaDine Portfolio
---

# Portfolio

Examples of my professional work:

{% assign doclist = site.portfolio | sort: 'title'  %}
<ul>
{% for page in doclist %}
    <li><a href="{{ page.url | absolute }}">{{ page.title }}</a></li>
{% endfor %}
</ul>
