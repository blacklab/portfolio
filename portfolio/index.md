---
layout: page
title: Portfolio
---

This is a short and most probably incomplete collection of my studies and work.

<ul>
{% for post in site.categories.portfolio %}
<li><a href="../{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

<ul>
{% for page in site.pages %}
    {% if page.category == "portfolio" %}
    <li><a href="../{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>
