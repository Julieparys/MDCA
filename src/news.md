---
layout: default
name: news
title: Digital Currency News
permalink: news/
color: magenta
banner: News
---

#News

{% for post in site.posts %}
<h4><a href="{{ post.url }}">{{ post.date | date_to_string }} - {{ post.title }}</a></h4>
{{ post.excerpt }}
<a href="{{ post.url }}">&raquo; Read more</a>
{% endfor %}
