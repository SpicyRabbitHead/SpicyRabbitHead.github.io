---
title: ''
summary: ''
date: 2026-08-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: |-
        I am currently a **PhD in Data Science** at the **City University of Hong Kong**, supervised by [**Prof. Kaidi Xu**](https://kaidixu.com/).
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: About
        education: ''
        interests: Research interests
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    id: research
    content:
      title: Research focus
      text: |-
        My current research interests include:

        - **Memory System of LLM**
        - **Embodied AI**
        - **AI for science**
    design:
      columns: '1'

  - block: collection
    id: publications
    content:
      title: Featured Publications
      count: 6
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: markdown
    id: awards
    content:
      title: Honors & awards
      text: |-
        - CityU MSDS Outstanding Dissertation Award (ranked 1st among 296 graduates)
        - IJCAI 2025 Student Volunteer
        - Nottingham Advantage Award - Graduation Promotion and Memento Project
        - Nottingham Advantage Award - Exchange Season
    design:
      columns: '1'

---

