---
layout: default
title: "Home"
---

# PDE / PINN 자료 정리

아래는 새로운 글 목록이야.

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
