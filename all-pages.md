---
layout: main
title: All Pages
permalink: /all-pages/
---
       {% for post in site.tags[this_word] %}{% if post.title != null %}
    <div class="tag-list">
        <span><a href="{{ post.url }}">{{ post.title }}</a></span>
        <small><span>| {{ post.date | date_to_string }}</span></small>
    </div>
    {% endif %}{% endfor %}

