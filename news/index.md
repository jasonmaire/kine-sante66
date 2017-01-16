---
layout: default
title: News
permalink: /news/
nav_order: 1
---

{% for post in site.categories.news %}
<a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
{{ post.content }}
{% endfor %}
