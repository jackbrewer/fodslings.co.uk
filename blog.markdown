---
layout: default
title: Useful Stuff
permalink: /blog/
---

<div class="container container--narrow">
  <ul class="blog-summary-list">
    {% for post in site.posts %}
      <li class="blog-summary prose">
        <a href="{{ post.url }}"><h2>{{ post.title }}</h2></a>
        <p>{{post.excerpt}}</p>
        <a href="{{ post.url }}">Read more</a>
      </li>
    {% endfor %}
  </ul>
</div>
