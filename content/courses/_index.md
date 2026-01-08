---
title: Coursework
summary: My Coursework
type: landing

cascade:
  - target:
      path: '{/coursework/*/**}'
    type: docs
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: coursework
    content:
      title: Coursework
      filters:
        tag: Coursework
        kinds:
          - section
    design:
      view: article-grid
      show_read_time: false
      show_date: false
      show_read_more: false
      columns: 1
---
