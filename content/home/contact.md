---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

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
      captcha: false

  # Contact details (edit or remove options as required)
  email: lixinze@math.utoronto.ca
  phone: 2899800166
  address:
    street: 45 St George St
    city: Toronto
    region: Ontario
    postcode: M5S 2E5
    country: Canada
    country_code: CA
  directions: PG301

design:
  columns: '2'
---
