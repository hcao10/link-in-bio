---
title: 'Home'
date: 2023-10-24
type: landing

design:
  background:
    image:
      # Add your image background to `assets/media/`.
      filename: bg-hue.svg

sections:
  - block: about.avatar
    content:
      # The user's folder name in content/authors/
      username: admin
  - block: buttons
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - title: Connect with me on LinkedIn
          icon: linkedin
          url: https://www.linkedin.com/in/haowei-cao
 - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Junior Software Developer
          company: Floauto Control Valve CO., LTD
          company_url: ''
          company_logo: org-gc
          location:Shanghai, China                                          
          date_start: '2020-10'
          date_end: '2021-06'
          description: |2-
              Responsibilities include:

              * Software Development
              * Hardware and software maintenance

        # - title: Professor of Semiconductor Physics
        #   company: University X
        #   company_url: ''
        #   company_logo: org-x
        #   location: California
        #   date_start: '2016-01-01'
        #   date_end: '2020-12-31'
        #   description: Taught electronic engineering and researched semiconductor physics.
    design:
      columns: '2'
---
