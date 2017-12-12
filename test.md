---
layout: default
title: Test
---

  {% include allpages.html %}
  {% for post in site.posts %}
  <span><p><a href="{{ post.url }}">{{ post.title }}</a></p></span>
  {% endfor %}
