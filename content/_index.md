---
# Leave the homepage title empty to use the site title
title: ''
summary: 'Research portfolio of Roberto Machado'
date: 2026-07-16
type: landing

sections:

  # Hero
  - block: dev-hero
    id: hero
    content:
      username: me
      greeting: "Hello, I’m"
      show_status: true
      show_scroll_indicator: true

      typewriter:
        enable: true
        prefix: "I work on"
        strings:
          - "spatial data science"
          - "geographic information science"
          - "urban and territorial analysis"
          - "explainable artificial intelligence"
          - "spatial literacy"
        type_speed: 70
        delete_speed: 40
        pause_time: 2500

      cta_buttons:
        - text: Explore My Projects
          url: "#projects"
          icon: arrow-down

        - text: Contact
          url: "#contact"
          icon: envelope

    design:
      style: centered
      avatar_shape: circle
      animations: true

      background:
        color:
          light: "#fafafa"
          dark: "#0a0a0f"

      spacing:
        padding: ["6rem", "0", "4rem", "0"]


  # Projects
  - block: portfolio
    id: projects

    content:
      title: "Research Projects"
      subtitle: "Selected projects in spatial data science, GIS and explainable AI"

      count: 0

      filters:
        folders:
          - projects

      buttons:
        - name: All
          tag: "*"

        - name: Spatial Data Science
          tag: Spatial Data Science

        - name: Urban Analysis
          tag: Urban Analysis

        - name: Explainable AI
          tag: Explainable AI

        - name: Open Science
          tag: Open Science

      default_button_index: 0

    design:
      columns: 3

      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"

      spacing:
        padding: ["4rem", "0", "4rem", "0"]


  # Research Tools and Methods
  - block: tech-stack
    id: tools

    content:
      title: "Research Tools and Methods"
      subtitle: "Technologies and analytical approaches used in my research"

      categories:

        - name: Programming and Data
          items:
            - name: Python
              icon: devicon/python

            - name: Jupyter
              icon: devicon/jupyter

            - name: PostgreSQL
              icon: devicon/postgresql

            - name: Git
              icon: devicon/git


        - name: Spatial Analysis
          items:
            - name: GeoPandas
              icon: devicon/python

            - name: OSMnx
              icon: devicon/python

            - name: Network Analysis
              icon: devicon/python

            - name: Spatial Statistics
              icon: devicon/python


        - name: Machine Learning and XAI
          items:
            - name: Scikit-learn
              icon: devicon/python

            - name: XGBoost
              icon: devicon/python

            - name: SHAP
              icon: devicon/python

            - name: LIME
              icon: devicon/python


        - name: Open and Interactive Research
          items:
            - name: GitHub
              icon: brands/github

            - name: Streamlit
              icon: devicon/python

            - name: Docker
              icon: devicon/docker

            - name: Open Science
              icon: brands/github

    design:
      style: grid
      show_levels: false

      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"

      spacing:
        padding: ["4rem", "0", "4rem", "0"]


  # Selected Experience
  - block: resume-experience
    id: experience

    content:
      title: "Selected Experience"
      date_format: Jan 2006

      items:

        - title: Geography Teacher
          company: Portuguese School of Dili
          company_url: ''
          company_logo: ''
          location: Dili, Timor-Leste
          date_start: '2026-03-27'
          date_end: ''
          description: |2-
            * Teaching Geography and digital technologies
            * Development of activities involving spatial reasoning and geographic information
            * Contribution to curriculum planning, assessment and departmental work


        - title: Visiting Researcher
          company: The University of Queensland
          company_url: 'https://www.uq.edu.au/'
          company_logo: ''
          location: Brisbane, Australia
          date_start: '2023-01-01'
          date_end: '2024-12-31'
          description: |2-
            * Research in geography, spatial data analysis and remote sensing
            * Development of computational approaches to geographic information
            * International collaboration in spatial data science


        - title: Strategic Adviser
          company: National Parliament of Timor-Leste
          company_url: ''
          company_logo: ''
          location: Dili, Timor-Leste
          date_start: '2021-01-01'
          date_end: '2022-12-31'
          description: |2-
            * Strategic and territorial analysis
            * Support for institutional planning and public policy
            * Preparation of evidence-based information for decision-making


        - title: Geographic Information and Territorial Planning Consultant
          company: Hexis
          company_url: ''
          company_logo: ''
          location: Portugal
          date_start: '2017-01-01'
          date_end: '2019-12-31'
          description: |2-
            * Geographic information systems and spatial analysis
            * Territorial planning and applied research
            * Preparation, processing and interpretation of spatial data

    design:
      columns: '1'

      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"

      spacing:
        padding: ["4rem", "0", "4rem", "0"]


  # Open Science
  - block: cta-card
    id: open-science

    content:
      title: "Open and Reproducible Research"

      text: |-
        My research combines open-source software, reproducible computational
        workflows, interactive applications and transparent analytical methods.

        Research code and notebooks are made available through GitHub whenever
        data licences and publication conditions permit.

      button:
        text: "View My GitHub"
        url: "https://github.com/RobertoOlivetree"
        icon: brands/github
        new_tab: true

    design:
      card:
        css_class: "bg-gradient-to-br from-primary-200 via-primary-100 to-secondary-200 dark:from-primary-600 dark:via-primary-700 dark:to-secondary-700"
        text_color: dark

      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"

      spacing:
        padding: ["4rem", "0", "4rem", "0"]


  # Contact
  - block: contact-info
    id: contact

    content:
      title: "Contact"

      subtitle: "Research collaboration and professional enquiries"

      text: |-
        I welcome enquiries concerning research collaboration, spatial data
        science, geographic information systems, urban and territorial
        analysis, explainable artificial intelligence and open science.

      email: roberto.machado@campus.fcsh.unl.pt
      autolink: true

    design:
      columns: '1'

      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"

      spacing:
        padding: ["4rem", "0", "6rem", "0"]
---
