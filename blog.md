---
layout: page
title: Blog
permalink: /blog/
---

# Blog

{% for post in site.posts %}
  <article>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p>{{ post.date | date: "%B %-d, %Y" }}</p>
  </article>
{% endfor %}