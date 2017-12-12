---
layout: default
title: Test
---

<section>
  {% include allpages.html %}
  {% for post in site.posts %}
  <span><p><a href="{{ post.url }}">{{ post.title }}</a></p></span>
  {% endfor %}
</section>
