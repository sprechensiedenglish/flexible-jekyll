---
layout: default
title: Test
---

<div>
  {% include allpages.html %}
  {% for post in site.posts %}
  <span><p><a href="{{ post.url }}">{{ post.title }}</a></p></span>
  {% endfor %}
</div>
