---
layout: default
title: Experiments
permalink: /experiments
---

<h1>{{ page.title }}</h1>

<p>A collection of my AI experiments and explorations. Here I document my hands-on work with different techniques, models, and approaches in artificial intelligence.</p>

<section class="posts-section">
    {% for post in site.posts %}
    {% if post.categories contains "experiments" %}
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
    {% endif %}
    {% endfor %}
</section>
