---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '100px'
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
        height: '140px'
        position: right
        color: '#666'
        brightness: 0.5
        media: organicchem.png
      link:
        icon: user
        icon_pack: fas
        text: Learn more
        url: ../people/
    - title: Academics, leadership and service...
      content: These three pillars have been the backbone of my work. 
      align: left
      background:
        height: '140px'
        position: center
        color: '#555'
        brightness: 0.7
        media: SLL-Heffernan-SL-Adaptation.png
      link:
        icon: magnifying-glass
        icon_pack: fas
        text: Learn more
        url: ../publications/
        
---
