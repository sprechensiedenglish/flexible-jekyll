---
layout: nocomment
title: All Pages
permalink: /all-pages/
---
  {% for post in site.posts %}
  <span><p><a href="{{ post.url }}">{{ post.title }}</a></p></span>
  {% endfor %}
