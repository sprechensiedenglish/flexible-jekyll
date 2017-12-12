---
layout: main
title: All Pages
---
<h1>All Pages</h1>
<section class="blog-tags">
  {% for post in site.posts %}
  <span><p><a href="{{ post.url }}">{{ post.title }}</a></p></span>
  {% endfor %}
</section>
