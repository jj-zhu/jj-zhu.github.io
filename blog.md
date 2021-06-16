---
layout: page
title: The Optimizer's Guide to a Good Life
permalink: /blog/
published: true
---
<h1>Recent posts</h1>

<div class="posts">
    {% for post in site.posts %}
    <article class="post">

        <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

        <div class="entry">
            {{ post.excerpt }}
        </div>

        <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
    {% endfor %}
</div>