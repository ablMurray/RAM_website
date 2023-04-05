---
widget: slider  # Use the Slider widget as this page section
widget_id: carousel
weight: 30
active: true  # Publish this section?
headless: true  # This file represents a page section.

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: 👋 Welcome to the group
      content:
      align: left
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: endofconference_outside.jpg
        fit: cover
      link:
        icon: 
        icon_pack: fas
        text: Meet the team
        url: ../people/
    - title: KCL Men's Health at EAU23!
      content: Take a look at what we've been working on
      align: right
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: alex_kfs_genderid.jpg
        fit: cover
    - title: KCL Men's Health at EAU23!
      content: Take a look at what we've been working on
      align: right
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: dan_presentation.jpg
        fit: cover
    - title: World-Class Semiconductor Lab
      content: 'Just opened last month!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: eric_presentation.jpg
        fit: cover
      # link:
        # icon: graduation-cap
        # icon_pack: fas
        # text: Join Us
        # url: ../contact/
---
