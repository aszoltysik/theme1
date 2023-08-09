---
layout: post
title: O nas
---

### O nas

Wyświetlanie postów bloga w ogranieczniem do 3

<ul class="related_posts">
  {% for post in site.related_posts limit: 3 %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
