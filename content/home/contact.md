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
      captcha: true
    
design:
  background:
    color: '#3a0000'
    text_color_light: true
  columns: '1'
  # css_style: 'padding-top: 0'

---



- [X] i accept the: {{% staticref "uploads/Datenschutzerklärung.pdf" "newtab" %}} terms of servcie {{% /staticref %}}