--- 
title: 'San Marcos'
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
      title: Cigar Vault San Marcos
      subtitle: test subtitle
      text: "122 N LBJ Dr, San Marcos, TX 78666<br>
      (512) 396-7473<br><br>"
      primary_action:
        text: Cigar Vault San Marcos Instagram
        url: https://www.instagram.com/thecigarvaultsm/?hl=en
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
          filename: cvsm.jpg
          filters:
            brightness: 0.5
  - block: cta-image-paragraph
    id: hours
    content:
      items:
        - title: Hours
          feature_icon: bolt
          features: 
            - "Sunday 10 AM – 8 PM"
            - "Monday 10 AM – 8 PM"
            - "Tuesday 10 AM – 9 PM"
            - "Wednesday 10 AM – 9 PM" 
            - "Thursday 10 AM – 9 PM"
            - "Friday 10 AM – 10 PM"
            - "Saturday 10 AM – 8 PM"
          image: cvsm.jpg
---
