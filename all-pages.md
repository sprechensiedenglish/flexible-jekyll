---
layout: main
title: All Pages
permalink: /all-pages/
---
<section class="blog-tags">
  <h1>All Pages</h1>
  {% for post in site.posts %}
  <span><a href="{{ post.url }}">{{ post.title }}</a></span>
  {% endfor %}
</section>


