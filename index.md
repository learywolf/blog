---
layout: page
title: 少壮不努力，长大作 IT
tagline: 菜鸟运维的技术博客
---
{% include JB/setup %}


##**文章列表**##



<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



