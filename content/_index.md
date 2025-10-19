---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/cv.pdf
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
        
  - block: resume-experience
    content:
      username: resume
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true
  - block: resume-experience
    content:
      title: Activities
      username: activities
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true
  - block: resume-languages
    content:
      title: Languages
      username: admin

  - block: collection
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - events
    design:
      view: card
  - block: collection
    content:
      title: IETF
      text: 'I also contribute to standardization work at the **Internet Engineering Task Force (IETF)**, the leading organization for developing internet standards and protocols. My contributions focus on attestation mechanisms for resource-constrained IoT devices. For details on my standardization activities, please visit the standardization page.'
      filters:
        folders:
          - ietf
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: fafa
    content:
      title: Fafa
      filters:
        folders:
          - fafa
---
