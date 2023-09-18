---
layout: default
---

# Welcome to ryou365's note.

Here are the latest posts:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
