---
layout: page
title: News
permalink: /news/
---

{% for post in site.categories.news %}
<a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
{{ post.content }}
{% endfor %}
