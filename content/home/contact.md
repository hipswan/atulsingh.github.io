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
  email: singhatularvind@gmail.com
  phone: (716) 617-9315
  address:
    street: 704 Spring St Apt E2013
    city: Seattle
    region: WA
    postcode: '98104'
    country: United States
    country_code: US
  # coordinates:
  #   latitude: '42.886448'
  #   longitude: '-78.878372'
  # directions: Near CVS Pharmacy
  # office_hours:
  #   - 'Monday 10:00 to 13:00'
  #   - 'Wednesday 09:00 to 10:00'
  appointment_url: 'https://calendly.com/singhatularvind/30min'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/atulsingh158'

design:
  columns: '2'
---
