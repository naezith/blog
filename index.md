---
layout: default
title: naezith
description: List of posts.
---
<h1>Archive</h1>
<ul>
    {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>