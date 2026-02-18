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
    <script async src="https://subscribe-forms.beehiiv.com/embed.js"></script>
    <iframe src="https://subscribe-forms.beehiiv.com/6bace3bc-517d-4d0d-95f6-4df2832c5198" class="beehiiv-embed" data-test-id="beehiiv-embed" frameborder="0" scrolling="no" style="width: 100%; max-width: 560px; height: 120px; margin: 0 auto; display: block; border-radius: 8px !important; background-color: #1a1a1a; box-shadow: 0 0 #0000; max-width: 100%;"></iframe>
    <p class="newsletter-note">Join thousands of subscribers. Unsubscribe anytime.</p>
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
