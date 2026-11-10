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
            margin-bottom: 45px;
            text-align: left;
          }

          #about .pai-about-layout {
            display: flex;
            align-items: flex-start;
            gap: 50px;
          }

          #about .pai-about-logo {
            width: 180px;
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
            font-size: 1.1rem;
            line-height: 1.9;
            text-align: left;
          }

          #about .pai-about-text p {
            margin-bottom: 24px;
          }

          #about .pai-about-text a {
            color: #000000;
          }

          @media (max-width: 767px) {
            #about .pai-about-layout {
              flex-direction: column;
              gap: 25px;
            }

            #about .pai-about-logo {
              width: 140px;
            }
          }
        </style>

        <h2 class="pai-about-title">ABOUT US</h2>

        <div class="pai-about-layout">
          <div class="pai-about-logo">
            <img src="icon.png" alt="PAI Lab logo">
          </div>
          <div class="pai-about-text">
            <p>The Psychiatry and AI (PAI) Lab is a cross-disciplinary research hub for medical AI and digital health research in psychiatry.</p>
            <p>Founded by Dr. Leo Lizhou Fan in 2025, the lab is based in the Department of Psychiatry, Faculty of Medicine, CUHK. We welcome motivated researchers in AI and digital health to join our research community.</p>
            <p>To learn more about our members, visit our <a href="people/">people page</a>. For collaboration and joining opportunities, please <a href="contact/">contact us</a>.</p>
          </div>
        </div>
    design:
      columns: '1'
      background:
        color: '#ffffff'
        text_color_light: false
      spacing:
        padding: ['80px', '20px', '80px', '20px']
---
