---
layout: default
title: Blog
---

# Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%d %b %Y" }}
    </li>
  {% endfor %}
</ul>
