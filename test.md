---
layout: default
title: Test
---
<div class="content-box clearfix">
  <article class="article-page">
  <div class="page-content">
    <div class="wrap-content">
      <header class="header-page">
        <h1 class="page-title">About</h1>
        <div class="page-date"><span>&nbsp;&nbsp;&nbsp;&nbsp;</span></div>
      </header>
  {% for post in site.posts %}
  <span><p><a href="{{ post.url }}">{{ post.title }}</a></p></span>
  {% endfor %}
 </div>
    </div> <!-- End Wrap Content -->
  </div> <!-- End Page Content -->
</article> <!-- End Article Page -->
