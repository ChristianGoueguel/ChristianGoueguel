---
title: 'Home'
date: 2023-10-24
type: landing

design:
  background:
    image:
      # Add your image background to `assets/media/`.
      filename: background.svg

sections:
  - block: biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: Selected research paper
          icon: academicons/arxiv
          url: https://pubs.rsc.org/en/content/articlehtml/2019/ja/c9ja00090a
        - text: Data Science
          icon: brands/medium
          url: https://medium.com/@christian.goueguel
        - text: Connect with me on LinkedIn
          icon: brands/linkedin
          url: https://ca.linkedin.com/in/christiangoueguel
---
