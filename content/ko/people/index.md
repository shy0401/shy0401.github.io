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
      title: '▶ 나를 소개합니다!'
      subtitle: ''
      text: 
    design:
      columns: '1'

  - block: collection
    content:
      id: section-1
      title: 섹션1
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
    id: contest
    content:
      title: 대회 및 경진대회
      subtitle: ''
      text: ''
      page_type: post
      count: 5
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      offset: 0
      order: desc
    design:
      view: date-title-summary
      spacing:
        padding: [0, 0, 0, 0]
---
