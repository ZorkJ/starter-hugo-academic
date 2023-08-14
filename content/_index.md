---
# Leave the homepage title empty to use the site title
title:
date: 2023-08-15
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    content:
      title: Research
      filters:
        folders:
          - research
      design:
        columns: '2'
        view: citation
---
