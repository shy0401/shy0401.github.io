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



sections:
- block: about.avatar
  content:
  username: 신하윤
  text: 전북대학교 컴퓨터인공지능학부 학부생입니다. 아래 버튼을 통해 저의 CV를 다운로드할 수 있습니다.

  button:
  text: Download CV
  url: uploads/resume.pdf

  links:
  - name: 전북대학교 컴퓨터인공지능학부
  url: 'https://csai.jbnu.ac.kr/csai/index.do'
  icon: fas globe
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

- block: contact
  content:
  position: center
  title: Contact
  text: |-
  <br> <span style="font-size:95%">전북대학교 컴퓨터인공지능학부로 찾아오시는 길(공대 7호관)</span> <br>
  <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d3133.3336544142727!2d127.134454!3d35.846051!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMzXCsDUwJzQ1LjgiTiAxMjfCsDA4JzA0LjAiRQ!5e0!3m2!1sko!2skr!4v1696304446555" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>

  email: white_shy@naver.com
  phone: 010-8815-8409
  address:
  street: 전북대학교 공과대학 7호관
  city: 전주시
  region: 전라북도
  postcode: '54896'
  country: 대한민국
  country_code: KO
  coordinates:
  latitude: '35.846051'
  longitude: '127.134454'
  directions:
  design:
  columns: '3'
---
