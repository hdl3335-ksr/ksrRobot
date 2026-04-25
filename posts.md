---
title: Posts
nav_order: 3
permalink: /posts/
---

# Posts

이제 이 페이지는 `_posts` 폴더에 있는 실제 Jekyll 블로그 글 목록을 보여줍니다.

## Latest posts

{% for post in site.posts %}
- [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
  {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
