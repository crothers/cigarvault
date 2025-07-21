---
title: 'Home'
date: 2025-07-04
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Cigar Vault Texas
      text: Cigars   -   Conversation   -   Community
      primary_action:
        text: Cigar Vault Story
        url: "/story/"
      secondary_action:
        text: Join the Community
        url: "/discord/"
      announcement:
        text: 
        link:
          text: "Read more"
          url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "black"
        image:
          # Add your image background to `assets/media/`.
          # filename: smoke-cloud-png-isolated-on-black-background.jpg
          filename: smoke.svg
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "4"
          description: |
            Cigar Vault Lounges   
            in Central Texas
        - statistic: "100+"
          description: |
            cigar brands carried  
        - statistic: "1000+"
          description: |
            Cigar Vault   
            community members
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
---
