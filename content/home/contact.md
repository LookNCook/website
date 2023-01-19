---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 80

title: Questions? Feedback? Let's chat!
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: netlify
    formspree:
      id: 
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false



design:
  background:
    color: '#1a0000'
    text_color_light: true
  columns: '1'
  #css_style: 'padding-bottom: 0'
---

<form>
  <input type="checkbox" id="consent" name="consent" > 
  <label for="consent">
  I accept the: {{% staticref "uploads/Datenschutzerklärung.pdf" "newtab" %}} terms of servcie {{% /staticref %}}
  </label>
  </input>
</form>