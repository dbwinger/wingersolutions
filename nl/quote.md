---
layout: default
title: "Offerte aanvragen"
lang: nl
permalink: /nl/quote/
---

# Offerte aanvragen

Vul het formulier in en je krijgt binnen één werkdag een reactie.

<form action="https://formspree.io/f/mvgevpzz" method="POST" class="quote-form">
  <input type="hidden" name="_subject" value="Nieuwe offerteaanvraag - Winger Solutions" />
  <input type="hidden" name="_next" value="{{ site.url }}{{ '/nl/contact/' | relative_url }}" />
  <p style="display:none">
    <label>Laat dit veld leeg
      <input type="text" name="_gotcha" />
    </label>
  </p>

  <label for="name">Naam*</label>
  <input type="text" id="name" name="name" required>

  <label for="email">Email*</label>
  <input type="email" id="email" name="email" required>

  <label for="company">Bedrijf</label>
  <input type="text" id="company" name="company">

  <label for="phone">Telefoon</label>
  <input type="tel" id="phone" name="phone">

  <label for="project">Project samenvatting*</label>
  <textarea id="project" name="project" rows="5" required></textarea>

  <label for="budget">Budgetrange</label>
  <select id="budget" name="budget">
    <option value="">Kies een range</option>
    <option value="under_5k">Onder €5k</option>
    <option value="5k_15k">€5k - €15k</option>
    <option value="15k_40k">€15k - €40k</option>
    <option value="40k_plus">€40k+</option>
  </select>

  <label for="timeline">Tijdlijn</label>
  <select id="timeline" name="timeline">
    <option value="">Kies een tijdlijn</option>
    <option value="asap">Zo snel mogelijk</option>
    <option value="1_3_months">1-3 maanden</option>
    <option value="3_6_months">3-6 maanden</option>
    <option value="flexible">Flexibel</option>
  </select>

  <label for="notes">Aanvullende details</label>
  <textarea id="notes" name="notes" rows="4"></textarea>

  <label>
    <input type="checkbox" name="portfolio" value="yes"> Ik wil graag portfolio-voorbeelden zien
  </label>

  <p style="font-size: 0.9em; color: #999; margin-top: 15px;">
    Door dit formulier in te dienen, gaat u akkoord met onze <a href="{{ '/nl/terms/' | relative_url }}">Algemene Voorwaarden</a> en <a href="{{ '/nl/privacy/' | relative_url }}">Privacyverklaring</a>. We gebruiken <a href="https://formspree.io/" target="_blank">Formspree</a> voor veilige verwerking.
  </p>

  <button type="submit" class="nav-link">Verstuur aanvraag</button>
</form>

---
**Wat je kunt verwachten**
- Gratis kennismaking van 30 minuten voor nieuwe klanten
- Uurtarief vanaf €110 (excl. btw), onder voorbehoud van schriftelijke overeenstemming; vaste prijs mogelijk bij duidelijk omschreven projecten
- Je ontvangt binnen één werkdag een bevestiging en opvolging
