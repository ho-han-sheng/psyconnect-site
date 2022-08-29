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
  loop: true
  # Duration of transition between slides (in ms)
  interval: 3500

content:
  slides:
    - title: 👋 Welcome to the group!
      content: Take a look at what we're working on...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: working.jpg
    - title: Events
      content: 'Attend talks, movie screenings and bond with your peers'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: zoom_stock.jpg
      link:
        icon: presentation
        icon_pack: custom
        text: Peek our upcoming events
        url: ../event/
    - title: PsyConnect Statistics Support Group
      content: 'Meet fellow psychology majors, bounce ideas, questions and seek help from your seniors!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: stats_avatar.jpg
      link:
        icon: link
        icon_pack: custom
        text: Join Us
        url: ../contact/
    - title: Want to find out more or contribute in a greater capacity?
      content: 'Get in touch with us!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: email.jpg
      link:
        icon: email
        icon_pack: custom
        text: Contact Us
        url: ../contact/
---
