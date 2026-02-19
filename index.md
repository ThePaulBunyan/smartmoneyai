---
layout: default
---

<div class="hero">
  <h1>AI Automation for Business</h1>
  <p>We help businesses automate operations, build AI employees, and scale with artificial intelligence. No coding required.</p>
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

<div class="cta-section">
  <h2>Want Us to Build Your AI?</h2>
  <p>We create custom AI employees and automation systems for businesses.</p>
  <a href="mailto:smartmoneyai@proton.me" class="cta-button">Contact Us</a>
</div>

<div class="newsletter-section">
  <div class="newsletter-content">
    <h2>Get Weekly AI Automation Tips</h2>
    <p>Learn how to automate your business, build AI employees, and attract more clients.</p>
    <div class="newsletter-form">
      <input type="email" id="newsletter-email" placeholder="Enter your email address">
      <button type="button" onclick="window.open('https://smartmoneyai-newsletter-acf23f.beehiiv.com', '_blank')">Subscribe</button>
    </div>
    <p class="newsletter-note">Join thousands of business owners. Unsubscribe anytime.</p>
  </div>
</div>
