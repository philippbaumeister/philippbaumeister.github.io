---
# Leave the homepage title empty to use the site title
title: 'CV'
date: 2024-01-16
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      
  - block: experience
    content:
      title: Positions
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Postdoctoral researcher
          company: DIVerse Exoplanet Redox State Estimations – DIVERSE 
          company_url: ''
          company_logo: FU-Berlin
          location: Freie Universität Berlin
          date_start: '2024-01-15'
          date_end: ''
          description: ''
        - title: Research Assistant
          company: "DFG Research Unit 2440: Matter Under Planetary Interior Conditions"
          company_url: 'https://www.for2440.uni-rostock.de/'
          company_logo: DLR
          location: German Aerospace Center (DLR) Berlin
          date_start: '2021-01-15'
          date_end: '2024-01-14'
        - title: Research Assistant
          company: "DFG-SPP 1992: Exploring the Diversity of Extrasolar Planets"
          company_url: 'https://www-astro.physik.tu-berlin.de/exoplanet-diversity/'
          company_logo: TU-Berlin
          location: Technische Universität Berlin
          date_start: '2018-01-15'
          date_end: '2021-01-14'
    design:
      columns: '2'
      
  - block: experience
    content:
      title: Education
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: PhD in Physics
          company: Technische Universität Berlin 
          company_url: ''
          company_logo: TU-Berlin
          location: Berlin
          date_start: '2018-01-15'
          date_end: '2023-11-09'
          description: ''
        - title: M.Sc. in Physics
          company: Technische Universität Berlin 
          company_url: ''
          company_logo: TU-Berlin
          location: Berlin
          date_start: '2015-06-01'
          date_end: '2017-11-21'
          description: ''
        - title: B.Sc. in Physics
          company: Technische Universität Berlin 
          company_url: ''
          company_logo: TU-Berlin
          location: Berlin
          date_start: '2011-10-01'
          date_end: '2015-06-01'
          description: ''
    design:
      columns: '2'
      
  - block: portfolio
    id: projects
    content:
      title: Projects I am/was involved with
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
#      buttons:
#        - name: All
#          tag: '*'
#        - name: Deep Learning
#          tag: Deep Learning
#        - name: Other
#          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
---
