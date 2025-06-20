---
layout: default
title: Blog
description: Latest blog posts and updates
---

# Blog

<div class="blog-posts">
  {% for post in site.posts %}
    <article class="blog-post-preview">
      <header class="post-preview-header">
        <h2 class="post-preview-title">
          <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        </h2>
        <div class="post-preview-meta">
          <time datetime="{{ post.date | date: '%Y-%m-%d' }}">
            {{ post.date | date: "%B %d, %Y" }}
          </time>
          {% if post.author %}
            <span class="post-author">by {{ post.author }}</span>
          {% endif %}
        </div>
      </header>
      
      <div class="post-preview-content">
        {% if post.excerpt %}
          {{ post.excerpt | strip_html | truncate: 200 }}
        {% else %}
          {{ post.content | strip_html | truncate: 200 }}
        {% endif %}
      </div>
      
      <footer class="post-preview-footer">
        <a href="{{ post.url | relative_url }}" class="read-more">Read more &rarr;</a>
        {% if post.tags.size > 0 %}
          <div class="post-preview-tags">
            {% for tag in post.tags %}
              <span class="tag">{{ tag }}</span>
            {% endfor %}
          </div>
        {% endif %}
      </footer>
    </article>
  {% endfor %}
  
  {% if site.posts.size == 0 %}
    <p class="no-posts">No blog posts yet. Check back soon!</p>
  {% endif %}
</div>
