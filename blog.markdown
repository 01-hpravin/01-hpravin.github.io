---
layout: default
title: Blog
permalink: /blog
---

<h1>{{ page.title }}</h1>

<section class="posts-section">
    {% for post in site.posts %}
    <div class="post-item">
        <div class="post-date">{{ post.date | date: "%Y %b %d" }}</div>
        <div class="post-content">
            <div class="post-title">
                <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
            </div>
            {% if post.excerpt %}
            <p>{{ post.excerpt | strip_html | truncatewords: 35 }}</p>
            {% endif %}
        </div>
    </div>
    {% endfor %}
</section>
