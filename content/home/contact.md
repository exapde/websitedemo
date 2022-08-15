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
  email: cuongng@mit.edu
  phone: 857-919-2820
  address:    
    street: 77 Massachusetts Avenue, Office 37-371
    city: Cambridge
    region: MA
    postcode: '02139'
    country: United States
    country_code: US
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: Enter Building 37 and take the elevator to Office 371 on Floor 3
  #office_hours:
  #  - 'Monday 10:00 to 13:00'
  #  - 'Wednesday 09:00 to 10:00'
  #appointment_url: 'https://calendly.com'
  contact_links:
    #- icon: twitter
    #  icon_pack: fab
    #  name: DM Me
    #  link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://mit.zoom.us/j/3899260143'

design:
  columns: '2'
---
