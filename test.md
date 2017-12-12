---
layout: default
title: Test
---
<aside class="sidebar">
  <header>
    <div class="about">
      <div class="cover-author-image">
        <a href="{{site.baseurl}}/"><img src="{{site.baseurl}}/assets/img/{% if site.author-img %}{{site.author-img}}{% endif %}" alt="{{site.author}}"></a>
      </div>
      <div class="author-name">{{site.author}}</div>
      <p>{{site.about-author}}</p>
      <p><a href="/about">About</a> | 
      <a href="/all-pages">All Pages</a></p>
    </div>
  </header> <!-- End Header -->
  <footer>
     <div class="copyright">
      
      <p>{{site.time | date: '%Y'}} &copy; {{site.author}}</p>
    </div>
  </footer> <!-- End Footer -->
</aside> <!-- End Sidebar -->
<div class="content-box clearfix">
  <article class="article-page">
  <div class="page-content">
    <div class="wrap-content">
      <header class="header-page">
        <h1 class="page-title">About</h1>
        <div class="page-date"><span>&nbsp;&nbsp;&nbsp;&nbsp;</span></div>
      </header>
      
      <p>{{site.time | date: '%Y'}} &copy; {{site.author}}</p>
    </div>

<div class="content-box clearfix">
  {% for post in site.posts %}
  <span><p><a href="{{ post.url }}">{{ post.title }}</a></p></span>
  {% endfor %}
    </div> <!-- End Wrap Content -->
  </div> <!-- End Page Content -->
</article> <!-- End Article Page -->
</div>
