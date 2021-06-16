---
layout: page
title: The Optimizer's Guide to a Good Life
permalink: /blog/
published: true
---
Here, I write about data-driven decision-making, robustness under uncertainty, how to live a good life.

<h2>Recent posts:</h2>
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