--- 
title: 'Bee Cave'
date: 2025-07-04
type: landing

design:
  # Default section spacing
  spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]

sections:
  - block: hero
    content:
      title: Cigar Vault Bee Cave
      subtitle: test subtitle
      text: "12703 State Hwy 71, Bee Cave, TX 78738<br>
      (512) 300-0027<br><br>"
      primary_action:
        text: Cigar Vault Bee Cave Instagram
        url: https://www.instagram.com/cigarvault_beecave/?hl=en
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
          filename: cvbc.jpg
          filters:
            brightness: 0.5
  - block: cta-image-paragraph
    id: hours
    content:
      items:
        - title: Hours
          feature_icon: bolt
          features: 
            - "Sunday 12 PM – 8 PM"
            - "Monday 12 PM – 8 PM"
            - "Tuesday 12 PM – 8 PM"
            - "Wednesday 12 PM – 8 PM" 
            - "Thursday 12 PM – 8 PM"
            - "Friday 12 PM – 10 PM"
            - "Saturday 12 PM – 10 PM"
          image: cvbc.jpg
---
