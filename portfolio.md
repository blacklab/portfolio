---
layout: page
title: Portfolio
permalink: /portfolio/
---

This is a short collection of my studies and work.

<ul>
{% for post in site.categories.portfolio %}
<li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
