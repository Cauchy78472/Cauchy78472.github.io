---
layout: page
title: Running
---

{% for post in site.posts %}
{% if post.tags contains "running" %}
<div class="diary-entry">
  <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  {{ post.excerpt }}
  <hr>
</div>
{% endif %}
{% endfor %}
