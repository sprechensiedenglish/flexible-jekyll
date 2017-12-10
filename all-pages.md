---
layout: main
title: All Pages
permalink: /all-pages/
---
<div class="wrap-content">
      <header class="header-page">
        <h1 class="page-title">All Pages</h1>
        <div class="page-date"><span>&nbsp;&nbsp;&nbsp;&nbsp;</span></div>
      </header>
  <ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
</div>


