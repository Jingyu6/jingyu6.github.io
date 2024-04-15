---
# Leave the homepage title empty to use the site title
title: ''
date: 2023-04-15
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Bio
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: AI Resident
          company: Meta AI
          company_url: https://ai.meta.com
          company_logo: org_meta
          location: Menlo Park, CA
          date_start: '2022-09-01'
          date_end: '2023-09-01'
          description: |2- 
            Research on large language models:

              * CodeLlama: SOTA open sourced code generation LLMs
              * Llama 2 Long: effective context length extension of Llama 2 up to 32K

            Research on 3D computer vision:

              * Semantic 3D indoor scene synthesis, reasoning, and planning
              * Text-guided 3D human generation
        - title: Research Assistant
          company: ETH Zurich
          company_url: https://las.inf.ethz.ch/krausea
          company_logo: org_eth
          location: Zurich, Switzerland
          date_start: '2022-03-01'
          date_end: '2022-11-01'
          description: Student research assistant working on offline reinforcement learning algorithms that train with a mixture of trajectories sampled from multiple demonstrators. 
        - title: Machine Learning Engineer
          company: ByteDance
          company_url: https://www.bytedance.com/en
          company_logo: org_bytedance
          location: Beijing, China
          date_start: '2020-08-01'
          date_end: '2021-08-01'
          description: Worked on the search engine in Douyin's E-commerce platform from the very early stage, including the search index, data pipeline, retrieval module, and ranking deep models. 
        - title: Teaching Assistant
          company: Courant Institute, New York University
          company_url: https://cims.nyu.edu/dynamic
          company_logo: org_nyu
          location: New York, NY
          date_start: "2018-09-01"
          date_end: "2019-05-01"
          description: Tutored students on computer system organization. 
    design:
      columns: '2'
  
  - block: collection
    id: publications
    content:
      title: Papers
      filters:
        folders:
          - publication
      order: desc
      design:
        columns: '2'
        view: card
  
  - block: markdown
    id: miscellaneous
    content:
      title: Miscellaneous
      text: |2-
        I was first trained as a game designer at [NYU Game Center](https://gamecenter.nyu.edu) during my undergrad and became increasingly more interested in CS and AI. Despite that, I'm still very interested in game dev, physically-based rendering, and game AI. 

        During my free time, I enjoy playing chess (my favorite [live-stream](https://www.youtube.com/@GMHikaru)), electric guitars (my favorite [instrumental band](https://www.youtube.com/@Polyphia)), and recently got obsessed with golf (a group of [chilled golfers](https://www.youtube.com/@GoodGood)). 
---
