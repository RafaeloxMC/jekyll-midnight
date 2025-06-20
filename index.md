---
layout: default
title: Home
description: A clean Jekyll theme for dark mode users
---

<div class="hero">
  <h1 class="hero-title">🌙 jekyll-midnight</h1>
  <p class="hero-subtitle">A beautiful, dark Jekyll theme designed for the modern developer</p>
  <div class="hero-buttons">
    <a href="https://github.com/RafaeloxMC/jekyll-midnight" class="btn btn-secondary">View on GitHub</a>
  </div>
</div>

<div class="demo-preview">
  <h2>🎨 See it in Action</h2>
  <p>Experience the clean, dark aesthetic that makes reading a pleasure</p>
  <!-- Add a screenshot or live preview here -->
</div>

---

## 🚀 Quick Start

<div class="quick-start">
  <div class="step">
    <div class="step-content">
      <h4>💻 Clone & Install</h4>
      <p>Get up and running in under 2 minutes</p>
      <code>git clone https://github.com/RafaeloxMC/jekyll-midnight.git</code>
    </div>
  </div>
  
  <div class="step">
    <div class="step-content">
      <h4>🎨 Customize</h4>
      <p>Edit <code>_config.yml</code> with your site details</p>
    </div>
  </div>
  
  <div class="step">
    <div class="step-content">
      <h4>🚀 Deploy</h4>
      <p>Push to GitHub Pages or your favorite hosting platform</p>
    </div>
  </div>
</div>

---

## ✨ Why Choose jekyll-midnight?

<div class="features-grid">
  <div class="feature-card">
    <h3>🌙 Dark Mode First</h3>
    <p>Built from the ground up for dark mode enthusiasts with AMOLED-friendly true blacks</p>
  </div>
  
  <div class="feature-card">
    <h3>⚡ Lightning Fast</h3>
    <p>Optimized for performance with minimal CSS and JavaScript for blazing-fast load times</p>
  </div>
  
  <div class="feature-card">
    <h3>📱 Fully Responsive</h3>
    <p>Looks perfect on desktop, tablet, and mobile devices with adaptive layouts</p>
  </div>
  
  <div class="feature-card">
    <h3>🎨 Developer Friendly</h3>
    <p>Beautiful syntax highlighting and clean typography for code readability</p>
  </div>
</div>

---

## 📝 Latest Updates

<div class="recent-posts">
  {% for post in site.posts limit:3 %}
    <article class="post-preview">
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      <p class="post-meta">{{ post.date | date: "%B %d, %Y" }}</p>
      <p>{{ post.excerpt | strip_html | truncate: 120 }}</p>
      <a href="{{ post.url }}" class="read-more">Read more →</a>
    </article>
  {% endfor %}
  
  <a href="/blog" class="view-all">View all posts →</a>
</div>

---

**Happy blogging** with _jekyll-midnight_! 🌙
