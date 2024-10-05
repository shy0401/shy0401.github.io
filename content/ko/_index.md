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
      
      username: 신하윤
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
      text: 이 페이지는 신하윤의 포트폴리오 사이트입니다.
    design:
      columns: '3'
      css_class: justify-text
      
  - block: slider
    content:
      slides:

        - title: <span style="font-size:70%">정보보안</span>
          content: <span style="font-size:70%">중요해지고 있는 정보보안 및 사이버 보안</span>
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
          content: <span style="font-size:70%">비전/데이터마이닝 분야에 적용 가능한 AI 기술 개발<span style="font-size:70%">
          align: center
          background:
            image:
              filename: Ai1.jpg
              filters:
                brightness: 0.5
            position: center
            color: '#d346e3'

        - title: <span style="font-size:70%">디지털포렌식</span>
          content: <span style="font-size:70%">사이버수사대 디지털포렌식 중요도 증가</span>
          align: center
          background:
            image:
              filename: forensic.jpg
              filters:
                brightness: 0.3
            position: center
            color: '#7986ba'

        - title: <span style="font-size:70%">Math</span>
          content: <span style="font-size:70%">데이터마이닝 및 AI 활용 수학 연구</span>
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
      title: 개발
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - coding
    design:
      view: community/custom_card  # 섹션 1에서 compact 뷰 사용
      columns: '3'
      css_class: justify-text

  - block: collection
    content:
      id: section-2
      title: 각종 대회
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
      title: 자격증
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
