--- 
title: 'East Austin'
date: 2025-07-04
type: landing

design:
  # Default section spacing
  spacing: "1rem"

sections:
  - block: hero
    content:
      title: Cigar Vault Buda
      subtitle: test subtitle
      text: "210 Main St, Buda, TX 78610<br>
      (512) 361-3289<br><br>"
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
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: markdown
    content:
      title: Hours
      text: "* Monday 12 PM - 8 PM<br>
          * Tuesday 10 AM - 9 PM<br>
          * Wednesday 10 AM - 9 PM<br>
          * Thursday 10 AM - 9 PM<br>
          * Friday 10 AM - 10 PM<br>
          * Saturday 10 AM - 10 PM<br>
          * Saturday 12 PM - 10 PM<br>"
---
