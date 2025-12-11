---
layout: default
title: "Request a Quote"
lang: en
permalink: /quote/
---

# Request a Quote

Fill out the form below and we'll get back to you within 2 business days.

<form action="https://formspree.io/f/mvgevpzz" method="POST" class="quote-form">
  <input type="hidden" name="_subject" value="New quote request - Winger Solutions" />
  <p style="display:none">
    <label>Leave this field empty
      <input type="text" name="_gotcha" />
    </label>
  </p>

  <label for="name">Name*</label>
  <input type="text" id="name" name="name" required>

  <label for="email">Email*</label>
  <input type="email" id="email" name="email" required>

  <label for="company">Company</label>
  <input type="text" id="company" name="company">

  <label for="phone">Phone</label>
  <input type="tel" id="phone" name="phone">

  <label for="project">Project summary*</label>
  <textarea id="project" name="project" rows="5" required></textarea>

  <label for="budget">Budget range</label>
  <select id="budget" name="budget">
    <option value="">Select a range</option>
    <option value="under_5k">Under €5k</option>
    <option value="5k_15k">€5k - €15k</option>
    <option value="15k_40k">€15k - €40k</option>
    <option value="40k_plus">€40k+</option>
  </select>

  <label for="timeline">Timeline</label>
  <select id="timeline" name="timeline">
    <option value="">Select a timeline</option>
    <option value="asap">ASAP</option>
    <option value="1_3_months">1-3 months</option>
    <option value="3_6_months">3-6 months</option>
    <option value="flexible">Flexible</option>
  </select>

  <label for="notes">Additional details</label>
  <textarea id="notes" name="notes" rows="4"></textarea>

  <p style="font-size: 0.9em; color: #999; margin-top: 15px;">
    By submitting this form, you agree to our <a href="{{ '/terms/' | relative_url }}">Terms & Conditions</a> and <a href="{{ '/privacy/' | relative_url }}">Privacy Policy</a>. We use <a href="https://formspree.io/" target="_blank">Formspree</a> to handle submissions securely.
  </p>

  <button type="submit" class="nav-link">Send request</button>
</form>

---
**What to expect**
- Free 30-minute consult for new clients
- Hourly rate starts at €110 (excl. VAT), subject to written agreement; fixed-price contracts considered for well-defined projects
- You'll receive a confirmation and follow-up within 48 hours
