---
layout: page
title: Sam Tripp - Blog
permalink: /blog/
heading: Blog
---

Check out my blog posts below :)
<ul class="posts">

    {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>