---
title: ''
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: collection
    id: papers
    content:
      title: Publications
      username: admin
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
---