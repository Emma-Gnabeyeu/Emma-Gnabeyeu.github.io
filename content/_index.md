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
      text: |
        Hi, welcome to my website! I am a Research Scientist in Mathematics at <a href="https://www.lpsm.paris/" style="color:#0056b3;"> LPSM Sorbonne Université</a>, working on stochastic analysis, optimal control, diffusion models, and statistics, with applications to mathematical finance and machine learning.

        Prior to this, I studied at <a href="https://www.polytechnique.edu" style="color:#0056b3;">École Polytechnique</a>, where I earned an engineering degree with a major in mathematics. I also obtained a Master’s degree in Probability and Finance from <a href="https://www.ip-paris.fr" style="color:#0056b3;">Institut Polytechnique de Paris</a>, jointly with <a href="https://www.sorbonne-universite.fr" style="color:#0056b3;">Sorbonne Université</a>, graduating with highest honors (*mention Très Bien*), and received a bachelor’s degree in Philosophy from <a href="https://dep-philo.parisnanterre.fr/le-departement" style="color:#0056b3;">Université Paris Nanterre</a>.
      
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

