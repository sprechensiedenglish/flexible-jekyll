---
layout: main
title: All Pages
permalink: /all-pages/
---
<section class="blog-tags">
  <h1>All Pages</h1>
  <ul>
  {% for post in site.posts %}
    <li>

              <span><a href="{{ post.url }}">{{ post.title }}</a></span>
    </li>
  {% endfor %}
</ul>
</section>


