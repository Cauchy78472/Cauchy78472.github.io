---
layout: page
title: Diary
---

{% for post in site.posts %}
  {% if post.tags contains "diary" %}
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    {{ post.excerpt }}
    <hr>
  {% endif %}
{% endfor %}
