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
    ({{ post.date | date: "%Y-%m-%d" }})
  </li>
{% endfor %}{% endraw %}
</ul>

Raw Liquid Test: {% raw %}{{ site.title }}{% endraw %}

Processed Liquid Test: {{ site.title }}