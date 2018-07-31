---
layout: page
title: Blog
description: 路漫漫其修远兮，吾将上下而求索！
keywords: 博客, Blog
comments: false
menu: 博客
permalink: /blog/
---

> 记录是为了更好的回忆。

<ul class="listing">
{% for blog in site.blog %}
{% if blog.title != "Blog Template" %}
<li class="listing-item"><a href="{{ blog.url }}">{{ blog.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
