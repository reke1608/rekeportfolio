---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '400px'
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: Welcome to my space...
      content: Here to contribute to societal development and inspire young people.
      align: left
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: Ochem.png
        fit: cover
      link:
        icon: user
        icon_pack: fas
        text: Learn more
        url: ../people/
    - title: Academics, leadership and service...
      content: These three pillars have been the backbone of my work. 
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: Homepage.png
        fit: contain
      link:
        icon: magnifying-glass
        icon_pack: fas
        text: Learn more
        url: ../publications/
        
---
