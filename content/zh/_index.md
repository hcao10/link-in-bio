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
- block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Feel free to get in touch using the contact information provided below. I am always open to communication and would be happy to hear from you should you have any inquiries or need assistance. Your messages are always welcome, and I will do my best to respond promptly.
      # Contact (add or remove contact options as necessary)
      email: pfa6v5u0 AT duck DOT com
      appointment_url: 'https://calendly.com/haoweicao'
      office_hours:
        - 'Tuesday 09:30 to 10:30'
        - 'Thursday 09:30 to 10:30'
      autolink: false
    design:
      columns: '2'
---
