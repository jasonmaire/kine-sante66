---
layout: page
title: Exercices
categories: exercises
---

{% for post in site.categories.exercises %}
<li><a href="{{ post.url }}">{{ post.title }}</a></li>
{{ post.content }}
{% endfor %}
