---
title: 'Solving The Dynamic Volatility Fitting Problem: A Deep Reinforcement Learning Approach'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me
  - Omar Karkar  
  - Imad Idboufous

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-10-12'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
# publication: In *International Join*
publication_short: In *IJCNN*

abstract: The volatility fitting is one of the core problems in the equity derivatives business. Through a set of deterministic rules, the degrees of freedom in the implied volatility surface encoding (parametrization, density, diffusion) are defined. Whilst very effective, this approach widespread in the industry is not natively tailored to learn from shifts in market regimes and discover unsuspected optimal behaviors. In this paper, we change the classical paradigm and apply the latest advances in Deep Reinforcement Learning(DRL) to solve the fitting problem. In particular, we show that variants of Deep Deterministic Policy Gradient (DDPG) and Soft Actor Critic (SAC) can achieve at least as-good as standard fitting algorithms. Furthermore, we explain why the reinforcement learning framework is appropriate to handle complex objective functions and is natively adapted for online learning.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Deep Reinforcement Learning (DRL)
  - Continuous State Action Spaces 
  - Stochastic and Continuous Control
  - Actor-Critic
  - Sequential Decision Making
  - Deep Reinforcement Learning in Stochastic Environment

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
#    doi: 10.5555/123456

# Custom links
links:
  - type: pdf
    url: "https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4991699"
#  - type: code
#    url: https://github.com/HugoBlox/kit
#  - type: dataset
#    url: https://github.com/HugoBlox/kit
  - type: slides
    url: ../uploads/PresentationVolFitting.pdf
  - type: poster
    url: ../uploads/Poster_RL_for_vol_IJCNN2025-_.pdf
#  - type: video
#    url: https://youtube.com
---
