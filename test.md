---
layout: nocomment
title: Test
---
 <section>
 {% for post in site.posts %}
  <span><p><a href="{{ post.url }}">{{ post.title }}</a></p></span>
  {% endfor %}
</section>
