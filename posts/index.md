---
title: Posts
layout: default
nav_order: 3
has_children: false
---

# Posts

`_posts` 폴더에 있는 글을 날짜순으로 모아보는 페이지입니다.

## Latest posts

{% for post in site.posts %}
- [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
  {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
