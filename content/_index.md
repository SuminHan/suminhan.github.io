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
      title: "🚀 Toward Future"
      subtitle: ''
      text: |-
        Found <a href="https://smarthillgames.com/">SmartHillGames.com</a>
        
        <ol>
            <li>Research Contact: <a href="mailto:suminkaist@gmail.com">suminkaist@gmail.com</a></li>
            <li>Business Contact: <a href="mailto:ceo@smarthillgames.com">ceo@smarthillgames.com</a></li>
        </ol>

    
    
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
