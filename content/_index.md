---
title: ''

summary: 'Research portfolio of Roberto Machado'

date: 2026-07-16

type: landing

sections:

###############################################################################
# HERO
###############################################################################

- block: dev-hero
  id: hero

  content:
    username: me

    greeting: "Hello, I'm"

    show_status: true
    show_scroll_indicator: true

    typewriter:
      enable: true

      prefix: "I develop open methods for"

      strings:
        - "building-level urban analytics"
        - "building-level population representation"
        - "spatial context modelling"
        - "reproducible urban decision support"

      type_speed: 70
      delete_speed: 40
      pause_time: 2500

    cta_buttons:

      - text: Explore My Projects
        url: "#projects"
        icon: arrow-down

      - text: GitHub
        url: "https://github.com/RobertoOlivetree"
        icon: brands/github

  design:

    style: centered
    avatar_shape: circle
    animations: true

    background:
      color:
        light: "#fafafa"
        dark: "#0a0a0f"

    spacing:
      padding: ["6rem","0","4rem","0"]

###############################################################################
# PROJECTS
###############################################################################

- block: portfolio
  id: projects

  content:

    title: "Research Projects"

    subtitle: >
      Open and reproducible methods for building-level urban analytics

    count: 0

    filters:

      folders:
        - projects

    buttons:

      - name: All
        tag: "*"

      - name: Building-Level Analytics
        tag: Building-Level Analytics

      - name: Population Representation
        tag: Population Representation

      - name: Spatial Context
        tag: Spatial Context

      - name: Accessibility
        tag: Accessibility

      - name: Open Research Software
        tag: Open Research Software

    default_button_index: 0

  design:

    columns: 3

    background:
      color:
        light: "#ffffff"
        dark: "#0d0d12"

###############################################################################
# SKILLS
###############################################################################

- block: tech-stack
  id: skills

  content:

    title: "Research Tools and Methods"

    subtitle: >
      Methods and tools for reproducible building-level urban analysis

    categories:

      - name: Spatial Data Engineering

        items:

          - name: Python
            icon: devicon/python

          - name: Pandas
            icon: devicon/python

          - name: NumPy
            icon: devicon/python

          - name: PostGIS
            icon: devicon/postgresql

      - name: Building and Network Analytics

        items:

          - name: GeoPandas
            icon: devicon/python

          - name: OSMnx
            icon: devicon/python

          - name: Network Analysis
            icon: devicon/python

          - name: Spatial Statistics
            icon: devicon/python

      - name: Spatial Modelling

        items:

          - name: Scikit-learn
            icon: devicon/python

          - name: XGBoost
            icon: devicon/python

          - name: SHAP
            icon: devicon/python

          - name: LIME
            icon: devicon/python

      - name: Reproducible Research

        items:

          - name: GitHub
            icon: brands/github

          - name: Streamlit
            icon: devicon/python

          - name: Docker
            icon: devicon/docker

          - name: Plotly
            icon: devicon/python

###############################################################################
# EXPERIENCE
###############################################################################

- block: resume-experience
  id: experience

  content:

    title: "Selected Experience"

    date_format: Jan 2006

    items:

      - title: Geography Teacher

        company: Portuguese School of Dili

        location: Dili, Timor-Leste

        date_start: '2026-03-27'

        description: |2-

          * Teaching Geography and Digital Technologies

          * Spatial reasoning and geographic information

          * Curriculum development and assessment

      - title: Visiting Researcher

        company: The University of Queensland

        location: Brisbane, Australia

        date_start: '2023-01-01'

        date_end: '2024-12-31'

        description: |2-

          * Research in GIScience and spatial data science

          * Building computational workflows for urban analysis

          * International collaboration in spatial analytics

      - title: Strategic Adviser

        company: National Parliament of Timor-Leste

        location: Dili, Timor-Leste

        date_start: '2021-01-01'

        date_end: '2022-12-31'

        description: |2-

          * Territorial analysis

          * Evidence-based public policy

          * Strategic spatial planning

###############################################################################
# OPEN SCIENCE
###############################################################################

- block: cta-card
  id: open-science

  content:

    title: "Open and Reproducible Research"

    text: |-

      My research develops open and reproducible computational methods
      for building-level urban analytics.

      Current work focuses on building-level population representation,
      spatial context modelling, network accessibility, data quality and
      uncertainty for urban and territorial decision-making.

      Research software, documentation and example workflows are shared
      through GitHub whenever licensing conditions permit.

    button:

      text: "View GitHub"

      url: "https://github.com/RobertoOlivetree"

      icon: brands/github

      new_tab: true

###############################################################################
# CONTACT
###############################################################################

- block: contact-info
  id: contact

  content:

    title: "Contact"

    subtitle: "Research collaboration"

    text: |-

      I welcome collaboration in building-level urban analytics,
      population representation, spatial context modelling,
      network accessibility and reproducible research software.

    email: roberto.machado@campus.fcsh.unl.pt

    autolink: true
