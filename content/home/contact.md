---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 70

title: Contact
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

  # Contact details (edit or remove options as required)
  email: siaemam@gmail.com
  phone: '+98 912 0039 440'
  address:
    street: 8 Babaei, Fayyaz
    city: Tehran
    region: Sattarkhan
    postcode: ''
    country: Iran
    country_code: IR
  coordinates:
    latitude: ''
    longitude: ''
  directions: ''
  office_hours: ''
  appointment_url: ''
  contact_links:
    - icon: telegram
      icon_pack: fab
      name: Telegram
      link: 'https://t.me/SIA1999'

design:
  columns: '2'
---
