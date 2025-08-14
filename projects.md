---
layout: default
title: Projects
---

# Projects

Visit my [GitHub](https://github.com/alan-ysy) to see what I'm working on.

<ul class="project-list">
    {% for post in site.categories.projects %}
        <li class="project-list-item">
            <h4><a href="{{ post.url }}">{{ post.title }}</a></h4>
            <small class="post-date">{{ post.date | date: "%B %d, %Y" }}</small>
        </li>
    {% endfor %}
</ul>