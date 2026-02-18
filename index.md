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
    <p>Every week: Top AI tools, market trends, crypto insights, and money tips.</p>
    <div class="newsletter-form">
      <input type="email" id="newsletter-email" placeholder="Enter your email address">
      <button type="button" onclick="window.open('https://smartmoneyai-newsletter-acf23f.beehiiv.com', '_blank')">Subscribe</button>
    </div>
    <p class="newsletter-note">Join thousands of subscribers. Unsubscribe anytime.</p>
  </div>
</div>

<script>
document.getElementById('newsletter-email').addEventListener('keypress', function(e) {
  if (e.key === 'Enter') {
    window.open('https://smartmoneyai-newsletter-acf23f.beehiiv.com', '_blank');
  }
});
</script>

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
