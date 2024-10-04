---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-03-25
type: landing

# Add default section spacing
design:
  spacing: "6rem"

sections:

  - block: features
    content:
      title: <span style="font-size:85%">나(신하윤)를 소개하는 포트폴리오 사이트</span>
      text: <br><span style="font-size:125%">전북대학교 컴퓨터인공지능학부 신하윤의 포트폴리오 페이지에 오신 것을 환영합니다.</span> <br><br>
      {{% cta cta_link="./portfolio" cta_text="포트폴리오 보기 →" %}}

  - block: slider
    content:
      slides:
        - title: <span style="font-size:70%">Recruit</span>
          content: |
            <div class="card">
              <a href="contact" class="card-image hover-overlay">
                <img src="/images/recruitment.jpg" alt="Recruitment Image" class="img-responsive" loading="lazy" style="margin-top: 15px;">
              </a>
              <div class="card-text">
                <div class="section-subheading article-title mb-1 mt-3">
                  <h4><a href="contact" target="_blank">Join Us</a></h4>
                </div>
                <div class="article-style">
                  <p>Interested in MacsLAB? We’re recruiting!</p>
                </div>
              </div>
            </div>
          align: center
          background:
            image:
              filename: recruitment.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: <span style="font-size:70%">AI</span>
          content: |
            <div class="card">
              <a href="AI" class="card-image hover-overlay">
                <img src="/images/Ai.jpg" alt="AI Development Image" class="img-responsive" loading="lazy" style="margin-top: 15px;">
              </a>
              <div class="card-text">
                <div class="section-subheading article-title mb-1 mt-3">
                  <h4><a href="AI" target="_blank">AI Development</a></h4>
                </div>
                <div class="article-style">
                  <p>Explore AI solutions for various specialized fields like Healthcare and Aerospace.</p>
                </div>
              </div>
            </div>
          align: center
          background:
            image:
              filename: Ai.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: <span style="font-size:70%">Healthcare</span>
          content: |
            <div class="card">
              <a href="healthcare" class="card-image hover-overlay">
                <img src="/images/healthcare.jpg" alt="Healthcare Development Image" class="img-responsive" loading="lazy" style="margin-top: 15px;">
              </a>
              <div class="card-text">
                <div class="section-subheading article-title mb-1 mt-3">
                  <h4><a href="healthcare" target="_blank">Healthcare Development</a></h4>
                </div>
                <div class="article-style">
                  <p>Develop AI solutions applicable in Healthcare and Medical fields.</p>
                </div>
              </div>
            </div>
          align: center
          background:
            image:
              filename: healthcare.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: <span style="font-size:70%">Mathematics</span>
          content: |
            <div class="card">
              <a href="mathematics" class="card-image hover-overlay">
                <img src="/images/mathematics.jpg" alt="Mathematics Research Image" class="img-responsive" loading="lazy" style="margin-top: 15px;">
              </a>
              <div class="card-text">
                <div class="section-subheading article-title mb-1 mt-3">
                  <h4><a href="mathematics" target="_blank">Mathematics Research</a></h4>
                </div>
                <div class="article-style">
                  <p>Research mathematical theories and optimization models for AI.</p>
                </div>
              </div>
            </div>
          align: center
          background:
            image:
              filename: mathematics.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: <span style="font-size:70%">Development</span>
          content: |
            <div class="card">
              <a href="development" class="card-image hover-overlay">
                <img src="/images/development.jpg" alt="Development Image" class="img-responsive" loading="lazy" style="margin-top: 15px;">
              </a>
              <div class="card-text">
                <div class="section-subheading article-title mb-1 mt-3">
                  <h4><a href="development" target="_blank">Full-Stack Development</a></h4>
                </div>
                <div class="article-style">
                  <p>Leverage cutting-edge technologies to build full-stack applications.</p>
                </div>
              </div>
            </div>
          align: center
          background:
            image:
              filename: development.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

    design:
      slide_height: '350px'
      slide_width: '100%'
      is_fullscreen: false
      loop: true
      interval: 3000

  - block: collection
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: markdown
    content:
      title: Recent Publications
      subtitle: ''
      text: |-
        Recent research work, collaborations, and contributions to various fields.
    design:
      columns: '1'

  - block: collection
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1

  - block: collection
    content:
      title: Notifications & News
      subtitle: ''
      text: ''
      page_type: post
      count: 5
      filters:
        category: ""
        tag: ""
        exclude_featured: false
      offset: 0
      order: desc
    design:
      view: date-title-summary
      spacing:
        padding: [0, 0, 0, 0]

  - block: cta-card
    demo: true
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open-source website builder trusted by 250,000+ academics like you.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        css_class: "bg-primary-700"
        css_style: ""
---
