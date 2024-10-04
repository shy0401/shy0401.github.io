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
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: 신하윤
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

        I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
        Please reach out to collaborate 😃
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

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
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
