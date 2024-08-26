---
layout: page
title: All Posts
permalink: /post-list/
---

# All Posts

<ul>
{% raw %}{% for post in site.posts %}
  <li>
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    <span>({{ post.date | date: "%Y-%m-%d" }})</span>
  </li>
{% endfor %}{% endraw %}
</ul>