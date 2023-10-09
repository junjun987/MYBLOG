---
date: "2022-10-24"
sections:
- block: about.biography
  content:
    title: Welcome
    username: admin
  id: about
- block: collection
  content:
    count: 10
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Research Experiences
  design:
    columns: "2"
    view: posts
  id: posts
- block: collection
  content:
    filters:
      featured_only: false
      folders:
      - publication
    title: Publications
  design:
    columns: "2"
    view: list
  id: featured
title: null
type: landing
---
