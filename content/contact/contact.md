---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
# weight: 130

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

  email: faroya2011@gmail.com
  phone: +33 6 65 69 69 19
  address:
    street: Centre Inria de l'université de Bordeaux
    city: Bordeaux  
    region: 
    postcode: '33300'
    country: France
    country_code: FR
  # coordinates:
  #   latitude: '37.4275'
  #   longitude: '-122.1697'
  directions: Centre Inria de l'université de Bordeaux <br/>
  200 Av. de la Vieille Tour, 33405 Talence
   office_hours:
     - 'Monday to Friday 10:00 to 17:00'
   #  - 'Wednesday 09:00 to 10:00'
  # appointment_url: 'https://calendly.com'
  # contact_links:
  #   - icon: twitter
  #     icon_pack: fab
  #     name: DM Me
  #     link: 'https://twitter.com/Twitter'
  #   - icon: video
  #     icon_pack: fas
  #     name: Zoom Me
  #     link: 'https://zoom.com'

design:
  columns: '2'
---
