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
  email: ""
  phone: ""
  address:
    city: The Hague
    region: NL-ZH
    country: Netherlands
    country_code: NL
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/dataandlyrics'
    - icon: keybase
      icon_pack: fab
      name: Chat
      link: 'https://keybase.io/reprexcommunity'

design:
  columns: '2'
---
