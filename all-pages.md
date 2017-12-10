---
layout: main
title: All Pages
permalink: /all-pages/
---
<h1>All Pages</h1>

  {% for post in site.posts %}
  <article>
    <h2>
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h2>
  </article>
{% endfor %}



