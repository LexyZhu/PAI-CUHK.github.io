---
title: Welcoming
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Welcome to the PAI Lab at CUHK
    
      text: |
        <style>
          @import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@1,800&display=swap');

          #section-hero .hero-lead {
            max-width: 56ch;
            margin-inline: auto;
            font-family: 'Montserrat', Arial, sans-serif;
            font-size: clamp(1rem, 1.8vw, 1.15rem);
            font-weight: 800;
            font-style: italic;
            line-height: 1.55;
          }
        </style>
        Connecting Minds, Shaping Futures—Pioneering Digital Mental Wellness through Innovative Algorithms.
        
    design:
      background:
        color: '#666'
        text_color_light: true
        image:
          filename: lab4.png
          size: cover
          position: right
          parallax: false
          filters:
            brightness: 0.7
      spacing:
        padding: ['140px', '20px', '140px', '20px']
      css_style: 'text-align: center;'

  - block: markdown
    id: about
    content:
      title: ''
      subtitle: ''
      text: |
        <style>
          #about .pai-about-title {
            color: #000000;
            font-size: 1.8rem;
            font-weight: 700;
            margin-bottom: 12px;
            text-align: left;
          }

          #about .pai-about-layout {
            display: flex;
            align-items: center;
            gap: 50px;
          }

          #about .pai-about-logo {
            width: 300px;
            flex-shrink: 0;
          }

          #about .pai-about-logo img {
            display: block;
            width: 100%;
            height: auto;
          }

          #about .pai-about-text {
            flex: 1;
            min-width: 0;
            color: #333;
            font-size: 1.0rem;
            line-height: 1.7;
            text-align: left;
          }

          #about .pai-about-text p {
            margin-bottom: 24px;
          }
          #about .pai-about-text p:last-child {
            margin-bottom: 0;
          }

          #about .pai-about-text a {
            color: #000000;
          }

          @media (max-width: 767px) {
            #about .pai-about-layout {
              flex-direction: column;
              gap: 25px;
            }
          }
        </style>

        <h2 class="pai-about-title">ABOUT US</h2>

        <div class="pai-about-layout">
          <div class="pai-about-logo">
            <img src="icon.png" alt="PAI Lab logo">
          </div>
          <div class="pai-about-text">
            <p>
              The Psychiatry and AI (PAI) Lab is an interdisciplinary research hub in the
              Department of Psychiatry, Faculty of Medicine, at The Chinese University of
              Hong Kong (CUHK). Founded in 2025 by
              <a href="https://lizhouf.github.io/">Prof. Leo Lizhou Fan</a>, the lab brings
              together faculty members, postdoctoral researchers, and students to explore
              how medical AI and digital health technologies can advance psychiatric
              research and care. Our research spans foundation models, embodied AI, and
              other applications of AI in mental health.
            </p>
          </div>
        </div>
    design:
      columns: '1'
      background:
        color: '#ffffff'
        text_color_light: false
      spacing:
        padding: ['80px', '20px', '20px', '20px']

  - block: markdown
    id: pai-news
    content:
      title: ''
      subtitle: ''
      text: |
        <style>
          #pai-news .pai-news-title {
            color: #000000;
            font-size: 1.8rem;
            font-weight: 700;
            margin-bottom: 45px;
            text-align: left;
          }
          #pai-news .pai-news-item + .pai-news-item {
            border-top: 1px solid #e5e5e5;
            margin-top: 20px;
            padding-top: 20px;
          }

          #pai-news .pai-news-item h3 {
            font-size: 1.15rem;
            margin: 0 0 6px;
          }

          #pai-news .pai-news-item time {
            display: block;
            color: #666;
            font-size: 0.9rem;
            margin-bottom: 6px;
          }

          #pai-news .pai-news-item p {
            margin: 0;
          }
        </style>

        <h2 class="pai-news-title">PAI News</h2>

        <article class="pai-news-item">
          <h3>Two Projects Win First Prize for Excellent Paper</h3>
          <time datetime="2026-04-16">April 16, 2026</time>
          <p>Two of our research projects received the First Prize for Excellent Paper at the 15th Chest Pain Center Conference.</p>
        </article>

        <article class="pai-news-item">
          <h3>Yu Huizi Receives Outstanding Award at GBA Graduate Research Forum</h3>
          <time datetime="2025-11-01">November 1, 2025</time>
          <p>Lab member Yu Huizi received the Outstanding Award for an academic oral presentation in science and engineering at the 2025 Greater Bay Area Graduate Research Forum.</p>
        </article>

        <article class="pai-news-item">
          <h3>Lab Team Wins Best Paper Award for Research on Medical Diagnostic Reasoning</h3>
          <time datetime="2025-01-01">January 1, 2025</time>
          <p>Our paper, “Enhancing Medical Diagnostic Reasoning with Chain-of-Thought in Large Language Models,” received a Best Paper Award.</p>
        </article>

        <!-- Add your lab updates here. -->
    design:
      columns: '1'
      background:
        color: '#ffffff'
        text_color_light: false
      spacing:
        padding: ['20px', '20px', '80px', '20px']
   
---
