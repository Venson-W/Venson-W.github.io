---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: 
    design:
      background:
        color: black
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename: peakpx.webp
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'Welcome 👋'
      subtitle: ''
      text: |-
        I'm a second-year PhD student in the Swiss Seismological Service & ETH Zürich. I am keen to understanding the across-scale behavior of fault slip / earthquake cycles, and in general, geological hazards.

        **Education:** 

        PhD in Geophysics, ETH Zürich, Feb. 2023 - present

        MEng in Geological Engineering, Tongji University, Sept. 2019 - Mar. 2022 
        
        BEng in Civil Engineering, Central South University, Sept. 2015 - Jun. 2019

        **Experience:** 

        CAE Algorithm Engineer, OptFuture (Peking), Sept. 2022 - Oct. 2022
        
        Exchange research student, Department of Civil Engineering, Monash University, Dec. 2018 - Jun. 2019

        **Software:** OpenFOAM, LIGGGHTS, CFDEM, PFC, FLAC 2D/3D, PyTorch
        
        **Toolkits:** Git, LaTeX, Markdown, Sketchup

        **Languages:** Mandarin, English

        **Journal Reviewer:** *Journal of Mountain Sciences*, *Earth and Space Science*

        **Memberships:** Student Member, European Geosciences Union (EGU)
    design:
      columns: '1'


  - block: collection
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
      view: compact
      columns: '1'
  
---
