---
layout: main
title: All Pages
permalink: /all-pages/
---
<h1>All Pages</h1>

  <ol>
  <li>
  {% for post in site.posts %}
  <a href="{{ post.url }}">{{ post.title }}</a>
  {% endfor %}
  <li>
</ol>


