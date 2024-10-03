---
widget: slider  # Use the Slider widget as this page section
weight: 1  # Position of this section on the page
active: true  # Publish this section?
headless: true  # This file represents a page section.

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '350px'
  slide_width: '150px'
  is_fullscreen: true
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 4000

content:
  slides:
    - title: <span style="font-size:90%">안녕하세요.</span>
      content: <span style="font-size:90%">이현우의 개인 페이지에 오신 것을 환영합니다!<span style="font-size:90%">
      align: center
      background:
        position: right
        color: '#000'
        brightness: 0.4
        media: award.jpg
        #fit: cover
    - title: Lunch & Learn ☕️
      content: Share your knowledge with the group and explore exciting new topics together!
      align: center
      background:
        position: center
        color: '#000'
        brightness: 0.4
        media: dongari.jpg
        #fit: cover
    - title: World-Class Semiconductor Lab
      content: 'Just opened last month!'
      align: right
      background:
        position: center
        color: '#000'
        brightness: 0.5
        media: dongari.jpg
        fit: cover
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: contact

---
