---
title: "Contact Us"
description: "Get in touch with Sai Sports Unit Academy. Book your free trial class, ask questions, or find us on the map."
draft: false
---

<section class="page-hero">
<h1>Get In Touch</h1>
<p>We'd love to hear from you. Book a free trial, ask a question, or just come say hello.</p>
</section>

<section class="section-block">
<div class="contact-grid">

<div class="contact-info">
<h2>Academy Information</h2>

<div class="contact-item">
<span class="contact-icon">📍</span>
<div>
<strong>Address</strong><br>
[Street Address]<br>
Gooty, Anantapur (Dist.), Andhra Pradesh
</div>
</div>

<div class="contact-item">
<span class="contact-icon">📞</span>
<div>
<strong>Phone</strong><br>
<a href="tel:08368156982">08368156982</a>
</div>
</div>

<div class="contact-item">
<span class="contact-icon">✉️</span>
<div>
<strong>Email</strong><br>
<a href="mailto:saisportsunit@gmail.com">saisportsunit@gmail.com</a>
</div>
</div>

<div class="contact-item">
<span class="contact-icon">🕐</span>
<div>
<strong>Office Hours</strong><br>
Mon – Fri: 00:00 PM – 00:00 PM<br>
Saturday: 00:00 AM – 00:00 PM<br>
Sunday: 00:00 AM - 00:00 PM
</div>
</div>

<div class="contact-social">
<!--<a href="https://facebook.com/yourpage" target="_blank" rel="noopener noreferrer" class="social-icon-link">📘 Facebook</a> -->
<a href="https://www.instagram.com/saisportsunit/" target="_blank" rel="noopener noreferrer" class="social-icon-link">📸 Instagram</a>
<!--<a href="https://youtube.com/@yourchannel" target="_blank" rel="noopener noreferrer" class="social-icon-link">▶️ YouTube</a> -->
</div>
</div>

<div class="contact-form-wrapper">
<h2>Send Us a Message</h2>
<p class="form-note">Fill in the form and we'll get back to you within 24 hours. Or <a href="tel:08368156982">call us</a> for a faster response.</p>

<form id="contactForm" class="contact-form" onsubmit="handleFormSubmit(event)">
  <div class="form-row">
    <div class="form-group">
      <label for="name">Your Name *</label>
      <input type="text" id="name" name="name" placeholder="John Smith" required>
    </div>
    <div class="form-group">
      <label for="phone">Phone Number</label>
      <input type="tel" id="phone" name="phone" placeholder="(000) 000-0000">
    </div>
  </div>
  <div class="form-group">
    <label for="email">Email Address *</label>
    <input type="email" id="email" name="email" placeholder="you@email.com" required>
  </div>
  <div class="form-group">
    <label for="interest">I'm interested in...</label>
    <select id="interest" name="interest">
      <option value="">— Select a program —</option>
      <option value="Little Tigers (Ages 4–7)">Little Tigers (Ages 4–7)</option>
      <option value="Junior Champions (Ages 8–14)">Junior Champions (Ages 8–14)</option>
      <option value="Teen & Adult (Ages 15+)">Teen & Adult (Ages 15+)</option>
      <option value="Other / General Enquiry">Other / General Enquiry</option>
    </select>
  </div>
  <div class="form-group">
    <label for="message">Message</label>
    <textarea id="message" name="message" rows="4" placeholder="Tell us a bit about yourself or your child, any questions you have, or preferred class times..."></textarea>
  </div>
  <button type="submit" class="btn-primary btn-full">Send via WhatsApp 📱</button>
</form>

<script>
function handleFormSubmit(e) {
  e.preventDefault();

  const name = document.getElementById('name').value.trim();
  const phone = document.getElementById('phone').value.trim();
  const email = document.getElementById('email').value.trim();
  const interest = document.getElementById('interest').value;
  const message = document.getElementById('message').value.trim();

  const text = `*New Enquiry - Sai Sports Unit Taekwondo Academy*%0A%0A` +
               `*Name:* ${name}%0A` +
               `*Phone:* ${phone || 'Not provided'}%0A` +
               `*Email:* ${email}%0A` +
               `*Interest:* ${interest || 'General Enquiry'}%0A` +
               `*Message:* ${message || 'No additional message'}%0A%0A` +
               `Sent from website contact form.`;

  const waNumber = '8886406452';
  const waUrl = `https://wa.me/${waNumber}?text=${text}`;

  window.open(waUrl, '_blank');
}
</script>
</div>
</section>

<section class="section-block section-dark">
  <h2 class="section-title">Find Us</h2>
  <div class="map-wrapper">
    <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d1738.536104912145!2d77.64205240171356!3d15.133848710020436!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e1!3m2!1sen!2sin!4v1783682272111!5m2!1sen!2sin" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="strict-origin-when-cross-origin"></iframe>
  </div>
</section>

<section class="section-block">
<h2 class="section-title">Frequently Asked Questions</h2>

<!--<div class="faq-list">

<div class="faq-item">
<h4>❓ Do I need any experience to join?</h4>
<p>Absolutely not. We welcome complete beginners of all ages. Your first class is free with no commitment.</p>
</div>

<div class="faq-item">
<h4>❓ What should I wear to my first class?</h4>
<p>Comfortable sportswear (tracksuit, shorts, t-shirt) is fine for your trial class. Once you enroll, we'll help you get the right uniform (dobok).</p>
</div>

<div class="faq-item">
<h4>❓ How long does it take to get a black belt?</h4>
<p>For a dedicated student training 2–3 times per week, the average time is 4–5 years. It varies by age, commitment, and natural progress.</p>
</div> -->

<div class="faq-item">
<h4>❓ Is Taekwondo safe for young children?</h4>
<p>Yes — with proper supervision and age-appropriate instruction, Taekwondo is one of the safest martial arts for children. Our Little Tigers classes are non-contact and focus on fun fundamentals.</p>
</div>

<!-- <div class="faq-item">
<h4>❓ Do you offer family discounts?</h4>
<p>Yes! We offer sibling and family membership discounts. Contact us for details.</p>
</div>

<div class="faq-item">
<h4>❓ What if I miss a class?</h4>
<p>We offer make-up classes for missed sessions. Just let your instructor know in advance when possible.</p>
</div> -->

</div>
</section>
