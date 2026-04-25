---
title: 홈
layout: home
nav_order: 1
---

# KSR Blog

사진, 메모, 짧은 감상을 차분하게 정리해 두는 블로그입니다.

## 둘러보기

- [포스트 목록]({{ site.baseurl }}/posts/)
- [소개]({{ site.baseurl }}/about/)

## 최근 글

{% assign latest_posts = site.posts | slice: 0, 5 %}
{% for post in latest_posts %}
- [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
  {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
