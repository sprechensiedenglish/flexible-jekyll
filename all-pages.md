---
layout: post
title: All Pages
permalink: /all-pages/
---
  <h1>All Pages</h1>
<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
  {% endfor %}
</ul>
