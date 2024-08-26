---
layout: default
title: Minimal Test
---

# Minimal Jekyll Test

1. Plain text
2. **Bold text**
3. Site title: {{ site.title }}
4. Base URL: {{ site.baseurl }}
5. Current year: {% raw %}{{ 'now' | date: "%Y" }}{% endraw %}
6. Loop test:
   {% raw %}{% for i in (1..3) %}
   - Item {{ i }}
   {% endfor %}{% endraw %}
7. Page URL: {{ page.url }}