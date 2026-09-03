---
layout: page
title: Dev
permalink: /dev/
---

## 분류

- [Algorithm]({{ "/dev/algorithm/" | relative_url }})
- [CS]({{ "/dev/cs/" | relative_url }})
- [Framework]({{ "/dev/framework/" | relative_url }})

## 전체 글

<ul class="post-list">
{% raw %}{% for post in site.categories.dev %}
  <li>
    <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
    <h3><a class="post-link" href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  </li>
{% endfor %}{% endraw %}
</ul>