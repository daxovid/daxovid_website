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
  email: dax@uga.edu
  address:
    street: 501 D. W. Brooks Drive
    city: Athens
    region: GA
    postcode: '30602'
    country: United States
    country_code: US
  coordinates:
    latitude: '33.94119577650493'
    longitude: '-83.37418610314653'
  directions: Enter Main CVM Building from D.W. Brooks Dr. Paid parking in Carlton Street Parking Deck S15.
  office_hours:
    - 'Please email to schedule a time'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: '[https://twitter.com/DaxOvid](https://twitter.com/DaxOvid)'

design:
  columns: '2'
---
