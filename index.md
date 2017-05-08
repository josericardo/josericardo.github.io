---
layout: default
---

# Latest Posts

{% for post in site.posts %}
## [](#header-2) {{ post.date | date: "%b %d, %Y" }}: <a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}
