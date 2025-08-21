--- 
title: 'Buda'
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
      title: Cigar Vault Buda
      subtitle: test subtitle
      text: "210 Main St, Buda, TX 78610<br>
      (512) 361-3289<br><br>"
      primary_action:
        text: Cigar Vault Buda Instagram
        url: https://www.instagram.com/the_cigarvault_buda/?hl=en
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
          filename: cvbu3.webp
          filters:
            brightness: 0.5
  - block: cta-image-paragraph
    id: hours
    content:
      items:
        - title: Hours
          feature_icon: bolt
          features: 
            - "Sunday 12 PM – 10 PM"
            - "Monday 12 PM – 8 PM"
            - "Tuesday 10 AM – 9 PM"
            - "Wednesday 10 AM – 9 PM" 
            - "Thursday 10 AM – 9 PM"
            - "Friday 10 AM – 10 PM"
            - "Saturday 10 AM – 10 PM"
          image: cvbu3.jpg
---
