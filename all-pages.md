---
layout: main
title: All Pages
permalink: /all-pages/
---
<section class="blog-tags">
  <h1>Tags in Blog</h1>
  <ul class="tags">
  {% for post in site.posts %}
    <li>
                  <div class="tag-list">

              <span><a href="{{ post.url }}">{{ post.title }}</a></span></div>
    </li>
  {% endfor %}
</ul>
</section>


