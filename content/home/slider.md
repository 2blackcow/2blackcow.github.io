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
    - title: <span style="font-size:90%">안녕하세요.</span>
      content: <span style="font-size:90%">이현우의 개인 페이지에 오신 것을 환영합니다!<span style="font-size:90%">
      align: center
      background:
        position: center
        color: '#000'
        brightness: 0.4
        media: hello.jpg
        #fit: cover
    - title:  <span style="font-size:90%">스터디</span>
      content:  <span style="font-size:90%">코드 및 언어를 지속적으로 공부합니다</span>
      align: center
      background:
        position: center
        color: '#000'
        brightness: 0.4
        media: study.jpg
        #fit: cover
    - title: <span style="font-size:90%">⬇️연락처⬇️</span>
      content: <span style="font-size:90%">언제든지 연락해주세요!</span>
      align: left
      background:
        position: center
        color: '#000'
        brightness: 0.4
        media: phone.jpg
        #fit: cover
      link:
        text: <span style="font-size:70%">연락처</span>
        icon: phone-alt
        icon_pack: fas
        url: contact

---
