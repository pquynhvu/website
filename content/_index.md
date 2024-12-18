---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-01-15
type: landing

design:
  spacing:
    margin: [0.5, 0.5, 0.5, 0.5]

sections:
  - block: resume-biography-3
    id: bio
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: quynhvu
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
      #view: compact
  
---
