---
layout: page
title: Essay
permalink: /essay/
---

<ul class="post-list">
{% raw %}{% for post in site.categories.essay %}
  <li>
    <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
    <h3><a class="post-link" href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  </li>
{% endfor %}{% endraw %}
</ul>