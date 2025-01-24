---
title: 'Résumé Jasper Wouters'
date: 2025-01-18
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Résumé
        url: uploads/JasperWouters_short_resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: iStock-808511278.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  # - block: skills
  #   content:
  #     title: Skills
  #     username: admin
  - block: features
    id : skills
    content:
      text: ""
      title: Skills
      username: admin
      items:
      - name: (single-cell) transcriptomics
        description: ''
        icon: custom/laptop-code-solid
      - name: Bioinformatics | Computational biology
        description: ''
        icon: custom/dna-solid
      - name: Single-cell CRISPR screens
        description: ''
        icon: custom/laptop-code-solid
      - name: (single-cell) epigenomics
        description: ''
        icon: custom/laptop-code-solid
      - name: R and RStudio
        description: ''
        icon: devicon/r
      - name: Unix
        description: ''
        icon: devicon/bash
      - name: Oncology
        description: ''
        icon: custom/regular-crab
      - name: AWS cloud computing
        description: ''
        icon: devicon/amazonwebservices-wordmark
      - name: (R) markdown
        description: ''
        icon: devicon/markdown
      - name: Git version control (gitlab, github, bitbucket)
        description: ''
        icon: devicon/git
      - name: VS Code
        description: ''
        icon: devicon/vscode-wordmark
      - name: High performance computing (HPC)
        description: ''
        icon: hero/cloud-arrow-up
      - name: Science communication
        description: ''
        icon: hero/chat-bubble-oval-left
      - name: Python
        description: ''
        icon: devicon/python
      - name: Docker
        description: ''
        icon: devicon/docker
      - name: (nextflow) pipelines (use of)
        description: ''
        icon: custom/list
      - name: Scientific writing
        description: ''
        icon: hero/document-text
      - name: Presentation skills
        description: ''
        icon: hero/presentation-chart-bar
      - name: Molecular and cell biology
        description: ''
        icon: academicons/ideas-repec
  # - block: awards
  #   content:
  #     title: Courses
  #     username: admin
  - block: languages
    content:
      title: Languages
      username: admin
---
