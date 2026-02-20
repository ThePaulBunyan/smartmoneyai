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
  </a>
  {% endfor %}
</div>

<a href="/services/" class="article-card" style="text-align: center; border-color: var(--accent);">
  <span class="tag">Services</span>
  <h2>Our Services & Pricing</h2>
  <p>Basic Automation from $499 + equipment. Full Workflow from $1,499. Monthly Management available.</p>
</a>

<div class="cta-section">
  <h2>Ready to Automate Your Business?</h2>
  <p>Get a free consultation. Tell us what you want to automate.</p>
  <a href="mailto:smartmoneyai@proton.me?subject=AI Automation Inquiry" class="cta-button">Email Us</a>
  
  <div class="contact-details">
    <p class="phone-number"><a href="tel:618-759-1617">618-759-1617</a></p>
    <p class="business-hours">Business Hours: 8am - 4pm CST</p>
  </div>
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
