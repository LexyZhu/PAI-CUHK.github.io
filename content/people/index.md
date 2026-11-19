---
title: People
date: 2022-10-24
type: landing

sections:
  - block: people
    content:
      title: Meet the Team
      user_groups:
        - Principle Investigator
        - Postdoctoral Fellow
        - PhD Students
        - Research Assistants & Interns
        - Affiliated Researchers
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true

  - block: markdown
    id: alumni
    content:
      title: ''
      text: |
        <style>
          #alumni {
            background: #fff !important;
          }

          #alumni .pai-alumni {
            max-width: 900px;
            margin: 0 auto;
            text-align: center;
          }

          #alumni .pai-alumni h2 {
            font-size: 1.8rem;
            font-weight: 400;
            margin: 0 0 36px;
          }

          #alumni .pai-alumni-grid {
            display: grid;
            grid-template-columns: repeat(2, minmax(0, 1fr));
            gap: 36px 48px;
          }

          #alumni .pai-alumni-name {
            font-size: 1.2rem;
            margin: 0 0 8px;
          }

          #alumni .pai-alumni-detail {
            color: #777;
            font-size: 0.9rem;
            line-height: 1.5;
            margin: 0;
          }

          @media (max-width: 640px) {
            #alumni .pai-alumni-grid {
              grid-template-columns: 1fr;
            }
          }
        </style>

        <div class="pai-alumni">
          <h2>Alumni</h2>
          <div class="pai-alumni-grid">
            <div>
              <p class="pai-alumni-name">Jieyi Wang</p>
              <p class="pai-alumni-detail">Research Assistant, 2025–2026<br>Now a PhD student at the National University of Singapore</p>
            </div>
            <div>
              <p class="pai-alumni-name">Wenjia Tan</p>
              <p class="pai-alumni-detail">Intern, 2025–2026<br>Now a PhD student at the University of Edinburgh</p>
            </div>
            <div>
              <p class="pai-alumni-name">Xinxin Lin</p>
              <p class="pai-alumni-detail">Intern, 2025–2026<br>Now a PhD student at the Chinese University of Hong Kong</p>
            </div>
            <div>
              <p class="pai-alumni-name">Lexuan Zhu</p>
              <p class="pai-alumni-detail">Intern, 2025–2026<br>Now a PhD student at the Chinese University of Hong Kong</p>
            </div>
          </div>
        </div>
    design:
      spacing:
        padding: ['24px', '20px', '64px', '20px']
---
