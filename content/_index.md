---
title: ''
summary: ''
type: landing

design:
  spacing: '5rem'

sections:
  # === Biography / Identity ===
  - block: resume-biography-3
    content:
      username: me # profile: me # === username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: Education
        interests: Research Interests
    design:
      background:
        gradient_mesh:
          enable: false
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  # === Awards ===
  - block: resume-awards
    content:
      title: Awards
      username: me # profile: me # ===username: me
      items:
        - title: First Prize – 2025 Best European Master's Thesis in Quantitative Finance.
          description: "First Prize for the 2025 edition of the best European master's thesis in Mathematical Finance: Award granted for an outstanding master’s thesis."
        - link: "https://natixis.groupebpce.com/fr/articles/prix-du-meilleur-memoire-de-master-de-finance-quantitative/"

  # === Research overview ===
  - block: markdown
    content:
      title: Research
      text: |-
        I am particularly interested in the interaction between
        stochastic modeling, optimal control, and data-driven
        methods, including reinforcement learning and probabilistic
        machine learning.
    design:
      columns: '1'

  # === Selected publications ===
  - block: collection
    content:
      title: Selected Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: citation

  # === Talks ===
  - block: collection
    content:
      title: Talks
      filters:
        folders:
          - events
    design:
      view: card
---

