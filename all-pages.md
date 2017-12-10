---
layout: main
title: All Pages
permalink: /all-pages/
---
<section>
  <h1>Tags in Blog</h1>
  
  <ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
</section>


