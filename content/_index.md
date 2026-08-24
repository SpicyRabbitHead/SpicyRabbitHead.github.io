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
        I work at the intersection of data science, machine learning, and real-world systems.
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
    id: about
    content:
      title: About
      text: |-
        I am **Tianshuo Wei**, also known online as **Weits** and **SpicyRabbitHead**. I am currently a PhD researcher in Data Science at the **City University of Hong Kong**, supervised by Prof. Kaidi Xu.

        My background combines mathematics, applied machine learning, software automation, and data analysis. I enjoy turning research questions into working systems and sharing useful experiments in public.
    design:
      columns: '1'

  - block: markdown
    id: research
    content:
      title: Research focus
      text: |-
        My current research interests include:

        - **Large language models** and memory mechanisms
        - **Embodied AI**, including security risks that connect digital attacks to physical-world harm
        - **AI for science**, with applications in scientific discovery and materials design
        - **Recommender systems** and multimodal representation learning
        - **Multimodal temporal data**, including EEG and eye-tracking signals
    design:
      columns: '1'

  - block: resume-experience
    id: experience
    content:
      username: me
    design:
      date_format: 'January 2006'
      is_education_first: false

  - block: markdown
    id: publications
    content:
      title: Selected publications
      text: |-
        - **Sustainable Materials Design with Multi-modal Artificial Intelligence**. *Advanced Science*, 2026. Co-first author.
        - **Feedback Is The Key for Automated Survey Generation**. *ACL 2026*. Co-first author.
        - **Bloom-Eval: A Hierarchical Evaluation Benchmark for Automatic Survey Generation Based on Bloom's Taxonomy**. *ACL 2026*. Co-first author.
        - **DANCE: Resource-Efficient Neural Architecture Search with Data-Aware and Continuous Adaptation**. *IJCAI 2025*. Co-first author.
        - **SPARK: Adaptive Low-Rank Knowledge Graph Modeling in Hybrid Geometric Spaces for Recommendation**. *CIKM 2025*. Co-first author.
        - **T-GINEE: A Tensor-based Multi-Graph Representation Learning**. *ICLR 2026*.

        Several additional works are under review at **SIGIR, IJCAI, DAC, KDD, and ICML**.
    design:
      columns: '1'

  - block: resume-skills
    id: skills
    content:
      title: Skills & tools
      username: me

  - block: resume-awards
    id: awards
    content:
      title: Honors & awards
      username: me

  - block: cta-card
    id: github
    content:
      title: Find me on GitHub
      text: |-
        Browse the code, follow new experiments, or say hello.
      button:
        text: Open GitHub profile
        url: https://github.com/SpicyRabbitHead
    design:
      card:
        css_class: 'bg-primary-600 text-white shadow-xl'
        css_style: ''
---
