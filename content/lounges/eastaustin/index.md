--- 
title: 'East Austin'
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
      title: Cigar Vault East Austin
      subtitle: test subtitle
      text: "2501 E Cesar Chavez St, Austin, TX 78702<br>
      (512) 861-5400<br><br>"
      primary_action:
        text: Cigar Vault East Austin Instagram
        url: https://www.instagram.com/cigarvaulteast/?hl=en
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
          filename: smoke.svg
          filters:
            brightness: 0.5
  - block: markdown
    id: hours
    content:
      title: Hours
      text: "* Sunday 12–10 PM<br>
          * Monday 12–8 PM<br>
          * Tuesday 12–8 PM<br>
          * Wednesday 12–8 PM<br>
          * Thursday 12–10 PM<br>
          * Friday 12–11 PM<br>
          * Saturday 12–11 PM<br>"
---
