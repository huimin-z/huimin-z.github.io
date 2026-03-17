---
layout: page
title: 归档
permalink: /archive/
---

<ul class="archive-list">
{% for post in site.posts %}
  <li>
    <span class="archive-date">{{ post.date | date: '%Y-%m-%d' }}</span>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
