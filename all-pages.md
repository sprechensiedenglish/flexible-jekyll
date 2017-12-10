---
layout: main
title: All Pages
permalink: /all-pages/
---
<span><h1>All Pages</h1></span>
<span>
  {% for post in site.posts %}
    <a href="{{ post.url }}">{{ post.title }}</a>
  {% endfor %}
</span>
