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
  - block: features
    content:
      title: Skills
      items:
        - name: Python
          description: 100%
          icon: python
          icon_pack: fab
	- name: R
          description: 100%
          icon: r-project
          icon_pack: fab
        - name: Statistics
          description: 100%
          icon: chart-line
          icon_pack: fas
---
