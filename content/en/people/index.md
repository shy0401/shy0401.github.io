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
      title: 🐇💖❤나를 소개합니다!🐇💖❤
      subtitle: ''
      text: 
    design:
      columns: '1'

  - block: collection
    content:
      id: section-1
      title: 대회
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - notification
    design:
      view: community/custom_card
      columns: '3'

  - block: collection
    content:
      id: section-2
      title: 자격증
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - notification
          - post
          - event
    design:
      view: community/custom_card
      columns: '3'

  - block: collection
    content:
      id: section-3
      title: 코딩 및 개발
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

---
