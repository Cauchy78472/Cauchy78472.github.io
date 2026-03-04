---
layout: page
title: Diary
---

{% for post in site.posts %}
  {% if post.tags contains "diary" %}
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt }}</p>
    <hr>
  {% endif %}
{% endfor %}
