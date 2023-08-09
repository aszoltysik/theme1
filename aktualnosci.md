---
layout: post
title: Aktualności
---

{% for post in site.posts %}
  <article>
    <h3>

        {{ post.title }}
      
    </h3>
    <time datetime="{{ post.date | date: "%Y-%m-%d" }}"> <p> {{ post.date | date_to_long_string }} </p></time>
    {{ post.content }}
  </article>
{% endfor %}
