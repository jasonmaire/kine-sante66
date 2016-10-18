---
layout: page
title: Exercices
categories: exercises
nav_order: 2
---

{% for post in site.categories.exercises %}
<li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
{{ post.content }}
{% endfor %}
