---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: 👋 Welcome to the group
      content: Take a look at what we're working on...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: coders.jpg
    - title: Traffic Stop
      content: 'We present the design of next-generation user interfaces for public safety organizations developed as the result of an extensive requirement analysis with the participation of public safety partners. The interfaces are proposed to leverage the futuristic capabilities of augmented reality displays of integrating virtual and real elements into simulated situational awareness scenarios in immersive virtual reality. Furthermore, we detail the assessment designs created to evaluate the interface elements proposed and conclude by reporting preliminary results gathered from informal observational studies.'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: traffic stop.jpg
    - title: World-Class Semiconductor Lab
      content: 'Just opened last month!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
