---
layout: page
title: Framework
permalink: /dev/framework/
---

<ul class="post-list">
{% for post in site.categories.framework %}
  <li>
    <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
    <h3><a class="post-link" href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  </li>
{% endfor %}
</ul>