---
# Leave the homepage title empty to use the site title
title: about page
description: 신하윤의 전북대학교 관련 정보
keywords: ["전북대학교", "신하윤", "컴퓨터인공지능"]
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: <span style="font-size:85%">신하윤의 포트폴리오 사이트</span>
      text: <br><span style="font-size:125%">전북대학교 컴퓨터인공지능학부 신하윤의 포트폴리오 페이지에 오신 것을 환영합니다.</span> <br><br>
        {{% cta cta_link="./portfolio" cta_text="포트폴리오 보기 →" %}}
    design:
      background:
        color: '#6b6a99'  # 배경 색상

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
            url: /people

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
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      loop: true
      interval: 3000
      background:
        color: '#6b6a99'  # 슬라이더 배경 색상

  - block: features
    id: features
    content:
      title: <span style="font-size:75%">My Interests</span>

      text: 저는 <br><br><br><br>
      items:
        - name: 인공지능(AI)
          icon: cogs
          icon_pack: fas
          description: <span style="font-size:90%">데이터마이닝 및 머신러닝 AI 기술 적용.</span><br><br>
        - name: 포렌식(Forensic)
          icon: fingerprint
          icon_pack: fas
          description:  <span style="font-size:90%">디지털포렌식 관련 분야 응용</span><br><br>
        - name: 수학(Medical Math)
          icon: square-root-alt
          icon_pack: fas
          description:  <span style="font-size:90%">데이터분류에 대한 통계 분석 모델링 관련 연구 수행.</span><br><br>
        - name: lock (Security)
          icon: comment-dots
          icon_pack: fas
          description:  <span style="font-size:90%">정보보안 관련 연구 및 학습.</span><br><br>
        - name: 개발 (Development)
          icon: laptop
          icon_pack: fas
          description:  <span style="font-size:90%">Full-Stack 기반의 응용 어플리케이션 개발.</span><br><br>
        - name: 글쓰기 (Writing)
          icon: pen
          icon_pack: fab
          description:  <span style="font-size:90%">글쓰기 관련 활동.</span><br><br>

    design:
      background:
        color: '#0f1fab'  # 배경 색상

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="/ko/people/" cta_text="Join team →" %}}
    design:
      columns: '1'
      background:
        color: '#6b6a99'  # 배경 색상 추가

  - block: about.avatar
    content:
      username: 신하윤
      text: ""
      button:
        text: "Download CV"
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: '#6b6a99'  # 아바타 배경
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
---
# 전북대학교
신하윤은 전북대학교 컴퓨터인공지능학부에서 재학중입니다.
