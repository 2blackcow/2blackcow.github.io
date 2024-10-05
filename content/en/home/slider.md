---
widget: slider  # Use the Slider widget as this page section
weight: 1  # Position of this section on the page
active: true  # Publish this section?
headless: true  # This file represents a page section.

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '350px'
  #slide_width: '150px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 3000

content:
  slides:
    - title: <span style="font-size:90%">Hello.</span>
      content: <span style="font-size:90%">Welcome to Hyunwoo Lee's personal page!<span style="font-size:90%">
      align: center
      background:
        position: center
        color: '#000'
        brightness: 0.4
        media: hello.jpg
        #fit: cover
    - title:  <span style="font-size:90%">Study</span>
      content:  <span style="font-size:90%">I continue to study code and language.</span>
      align: center
      background:
        position: center
        color: '#000'
        brightness: 0.4
        media: study.jpg
        #fit: cover
    - title: <span style="font-size:90%">⬇️Contact⬇️</span>
      content: <span style="font-size:90%">Please contact me anytime!</span>
      align: left
      background:
        position: center
        color: '#000'
        brightness: 0.4
        media: phone.jpg
        #fit: cover
      link:
        text: <span style="font-size:70%">contact</span>
        icon: phone-alt
        icon_pack: fas
        url: contact

---
