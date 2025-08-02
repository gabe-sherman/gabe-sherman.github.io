---
layout: page
title: Blog
permalink: /blog/
---

## All Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span style="color: #888;">({{ post.date | date: "%b %-d, %Y" }})</span>
    </li>
  {% endfor %}
</ul>