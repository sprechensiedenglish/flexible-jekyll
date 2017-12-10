---
layout: main
title: All Pages
permalink: /all-pages/
---
<h1>All Pages</h1>

  {% for post in site.posts %}
  <ol><li><a href="{{ post.url }}">{{ post.title }}</a><li></ol>
  {% endfor %}


