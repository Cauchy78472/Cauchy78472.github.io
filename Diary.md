---
layout: page
title: Diary
---
{% for post in site.posts %}
  {% if post.tags contains "diary" %}
    <div class="diary-entry">
      <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
      {{ post.excerpt }}
      <hr>
    </div>
  {% endif %}
{% endfor %}
