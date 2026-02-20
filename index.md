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

<div class="services-section">
  <h2>Services & Pricing</h2>
  
  <div class="service-card">
    <h3>Basic Automation</h3>
    <p class="price">$497 + $1,499 equipment</p>
    <p>One specific task automated</p>
    <ul>
      <li>Dedicated Mac Mini setup</li>
      <li>Email automation</li>
      <li>Auto-responders</li>
      <li>Follow-up sequences</li>
      <li>5 business days delivery</li>
    </ul>
  </div>
  
  <div class="service-card featured">
    <h3>Full Workflow</h3>
    <p class="price">$1,497 + $1,499 equipment</p>
    <p>Complete process automation</p>
    <ul>
      <li>Dedicated Mac Mini setup</li>
      <li>Up to 5 automations</li>
      <li>Custom AI employee</li>
      <li>Integration setup</li>
      <li>14 business days delivery</li>
    </ul>
  </div>
  
  <div class="service-card">
    <h3>Enterprise</h3>
    <p class="price">$2,997+</p>
    <p>Full business automation</p>
    <ul>
      <li>Custom equipment quote</li>
      <li>Unlimited automations</li>
      <li>Multiple AI employees</li>
      <li>Advanced integrations</li>
      <li>Ongoing support</li>
    </ul>
  </div>
  
  <div class="service-card">
    <h3>Monthly Management</h3>
    <p class="price">$297/mo</p>
    <p>Keep your AI running</p>
    <ul>
      <li>Monitor & optimize</li>
      <li>Add new automations</li>
      <li>24/7 support</li>
      <li>Monthly reports</li>
    </ul>
  </div>
</div>

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
