---
layout: default
title: archive
---
<h1>{{ page.title }}</h1>
<ul>
    {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}#disqus_thread" title="{{ post.title }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>