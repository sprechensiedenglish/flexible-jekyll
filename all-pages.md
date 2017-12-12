---
layout: main
title: All Pages
permalink: /all-pages/
---
<section class="blog-tags">
  <header class="header-page">
  <h1 class="page-title">All Pages</h1>
    <div class="page-date"><span>&nbsp;&nbsp;&nbsp;&nbsp;</span></div>
  </header>
  {% for post in site.posts %}
  <span><p><a href="{{ post.url }}">{{ post.title }}</a></p></span>
  {% endfor %}
</section>


