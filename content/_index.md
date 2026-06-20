---
title: 'Sarah A. Lang'
date: 2026-06-20
type: landing

design:
  background:
    image:
      # Add your image background to `assets/media/`.
      filename: bg-hue.svg

sections:
  - block: resume-biography
    content:
      # The user's folder name in content/authors/
      username: me
    design:
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: bio and publications on my website
          icon: academicons/cv
          url: https://sarahalang.com/
        - text: Digital Humanities YouTube channel
          icon: brands/youtube
          url: https://www.youtube.com/@sarahalang
        - text: Digital Humanities blog
          icon: brands/wordpress
          url: https://latex-ninja.com/
        - text: blog (epigrammetry) on Academic Self Help 
          icon: academicons/hypothesis
          url: https://epigrammetry.hypotheses.org/
---
