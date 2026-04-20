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
      username: me
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
      username: me
      items:
        - title: Prix du meilleur mémoire de Master de Finance Quantitative
          description: Prix décerné par Natixis pour un mémoire exceptionnel en finance quantitative.
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

