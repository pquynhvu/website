---
title:
type: landing
sections:
  - block: resume-biography-3
    id: about_me
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: quynhvu
  - block: collection
    id: publications
    content:
      title: Recent Publications
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
      email: l.toni@ucl.ac.uk
      address:
        street: Gower Street
        city: London
        region:
        postcode: 'WC1E 7JE'
        country: UK
        country_code: UK
      coordinates:
        latitude: '51.52341496502994'
        longitude: '-0.1324558153455622'
      directions: Malet Place Engineering Building
      office_hours:
      appointment_url:
      contact_links:
    design:
      columns: '2'
---
