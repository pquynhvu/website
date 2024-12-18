---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-01-15
type: landing

sections:
  - block: resume-biography-3
    id: bio
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: papers
    content:
      title: Publications & Projects
      text: |-
        {{% callout note %}}
          Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Let's get in touch! Drop me a line through the form below and I'll get back to you at my earliest convenience.
      #phone: (+ 1) 416-897-7663
      email: pquynhvu@outlook.com
      #appointment_url: 'https://calendly.com'
      #contact_links:
        #- icon: skype
          #icon_pack: fab
          #name: Skype
          #link: 'live:.cid.996a0491c4f0a7a3'
        #- icon: video
          #icon_pack: fas
          #name: Zoom Me
          #link: 'https://zoom.com'
      address:
        street: 234 Griffin-Floyd Hall
        city: Gainesville
        region: Florida
        postcode: '32601'
        country: United States
        country_code: US
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
        #- 'Monday 10:00 to 13:00'
        #- 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      #coordinates:
        #latitude: '37.4275'
        #longitude: '-122.1697'  
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
      columns: '2'
---
