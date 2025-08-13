---
layout: default
title: Posts
---
<h1>Posts</h1>
<ul class="post-list">
    {% for post in site.posts %}
        <li class="post-list-item">
            <h4><a href="{{ post.url }}">{{ post.title }}</a></h4>
            <small class="post-date">{{ post.date | date: "%B %d, %Y" }}</small>
        </li>
    {% endfor %}
</ul>