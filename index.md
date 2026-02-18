---
layout: default
---

<div class="hero">
  <h1>Master Your Money with AI</h1>
  <p>Discover the best AI tools for personal finance, investing, and wealth building. Expert reviews, tutorials, and strategies.</p>
</div>

<div class="newsletter-section">
  <div class="newsletter-content">
    <h2>Get Weekly AI Finance Updates</h2>
    <p>Every week: Top AI tools, market trends, crypto insights, and money tips. No spam, just value.</p>
    <form class="newsletter-form" action="#" method="POST">
      <input type="email" name="email" placeholder="Enter your email" required>
      <button type="submit">Subscribe</button>
    </form>
    <p class="newsletter-note">Join 1,000+ subscribers. Unsubscribe anytime.</p>
  </div>
</div>

<div class="article-list">
  {% for post in site.posts %}
  <a href="{{ post.url }}/" class="article-card">
    <span class="tag">{{ post.categories }}</span>
    <h2>{{ post.title }}</h2>
    <p>{{ post.excerpt | strip_html | truncate: 150 }}</p>
    <div class="meta">
      <span>{{ post.date | date: "%B %d, %Y" }}</span>
    </div>
  </a>
  {% endfor %}
</div>
