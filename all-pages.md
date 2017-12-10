---
layout: main
title: All Pages
permalink: /all-pages/
---
<h1>All Pages</h1>
  {% for post in site.posts %}
  <p>
  <a href="{{ post.url }}">{{ post.title }}</a></p>
  {% endfor %}


