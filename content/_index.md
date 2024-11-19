---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: use-svg-as-background-image-particle-strokes.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false


  - block: markdown
    content:
      title: '🚀 My Future Dream'
      subtitle: ''
      text: |-
        Daejeon is a very nice city where <a href="https://www.kaist.ac.kr/en/">SCIENCE</a> and <a href="https://www.instagram.com/fcd_ance/?__coig_challenged=1">ART</a> are growing harmoniously.
        I am dreaming of building a startup among the various career path options, whose ultimate goal is described in this <a href="./post/20241118-urban-space-robot/">ESSAY</a>.
    
        If you want to have a talk or discuss, contact this email: hsm6911 (at) gmail.com
    
    design:
      view: article
      spacing:
        padding: [20, 20, 20, 20]




  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2


  - block: collection
    id: blog
    content:
      title: Recent Blog Post
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 4
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: article-grid
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]



  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article
      spacing:
        padding: [20, 20, 20, 20]
    
---
