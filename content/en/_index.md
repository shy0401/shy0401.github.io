---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  spacing: "6rem"

sections:
  - block: about.avatar
    content:
      
      username: Shin Ha-yoon
      text: ""
      
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background: 
        color: black
        
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
          
  - block: markdown
    content:
      title: '📚 My Portfolio'
      subtitle: ''
      text: This page is Shin Ha-yoon's portfolio site.
    design:
      columns: '3'
      css_class: justify-text
      
  - block: slider
    content:
      slides:

        - title: <span style="font-size:70%">information security</span>
          content: <span style="font-size:70%">Information security and cyber security is becoming more important안</span>
          align: center
          background:
            image:
              filename: security1.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#1dc6f5'
          link:
            icon: user
            icon_pack: fas
            text: <span style="font-size:60%">Join Us</span>
            text-color: '#154ed4'
            url: contact

        - title: <span style="font-size:70%">AI</span>
          content: <span style="font-size:70%">Development of AI technology applicable to vision/data mining field<span style="font-size:70%">
          align: center
          background:
            image:
              filename: Ai1.jpg
              filters:
                brightness: 0.5
            position: center
            color: '#d346e3'

        - title: <span style="font-size:70%">Digital forensics</span>
          content: <span style="font-size:70%">Cyber Investigation Unit's Digital Forensics Increase in Importance</span>
          align: center
          background:
            image:
              filename: forensic.jpg
              filters:
                brightness: 0.3
            position: center
            color: '#7986ba'

        - title: <span style="font-size:70%">Math</span>
          content: <span style="font-size:70%">Research on Mathematics Using Data Mining and AI</span>
          align: center
          background:
            image:
              filename: mathematics1.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#bd4646'


    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '600px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000


  - block: collection
    content:
      id: section-1
      title: Development
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - coding
    design:
      view: community/custom_card 
      columns: '3'
      css_class: justify-text

  - block: collection
    content:
      id: section-2
      title: Contests
      subtitle: ''
      text: ''
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - notification
    design:
      view: community/custom_compact  # 섹션 2에서 list 뷰 사용
      columns: '3'
      css_class: justify-text

  - block: collection
    content:
      id: section-3
      title: Certificate
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - event
    design:
      view: community/grid  # 섹션 3에서 grid 뷰 사용
      columns: '3'
      css_class: justify-text


---
