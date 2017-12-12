---
layout: post
title: Test
---
<section class="blog-tags">
  {% for post in site.posts %}
  <span><p><a href="{{ post.url }}">{{ post.title }}</a></p></span>
  {% endfor %}
</section>
