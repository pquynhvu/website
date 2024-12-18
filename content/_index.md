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
      view: 3
      columns: '2'
---
