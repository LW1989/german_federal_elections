---
layout: default
title: Minimal Test
---

# Updated Minimal Jekyll Test

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
8. Simple variable test: {% assign test_var = "Hello, World!" %}{{ test_var }}
9. Simple if test: {% if true %}This should appear{% endif %}
10. Raw tag test: {% raw %}{{ This should not be processed }}{% endraw %}