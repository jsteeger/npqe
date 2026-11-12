---
title: "New Perspectives on Quantum Epistemology"
summary: "The official website for the workshop New Perspectives on Quantum Epistemology, April 1-2, 2027."
date: "2026-11-01"
type: "landing"

sections:

  - block: "hero"
    content:
      title: "New Perspectives on Quantum Epistemology"
      eyebrow: "Academic Workshop"
      text: "Join our two-day workshop!"
      # announcement:
      #   badge:
      #     text: "NEW"
      #     color: "primary"
      #   text: "Early bird registration open"
      primary_action:
        text: "Register Now"
        style: "gradient"
        icon: "hero/rocket-launch"
        url: "#registration"
      secondary_action:
        text: "Learn More"
        url: "#schedule"
      media: {}
    design:
      css_class: dark
      background:
        image:
          filename: backgrounds/hero.jpg
          filters:
            # blur: 6px        # Creates the soft, fuzzy look
            brightness: 0.6  # Dims the image slightly so text pops
      spacing:
        padding:
          - "1rem"
          - "0"
          - "4rem"
          - "0"
      no_padding: true
      size: "compact"
      layout: "centered"
      alignment: "center"
    ce: "section-welcome"
    id: "welcome"
    As: "section-10abbff3"

  - block: "markdown"
    content:
      title: "About"
      text: "Photo by [Danny Lines](https://unsplash.com/@dannylines?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Upsplash](https://unsplash.com/photos/purple-and-black-abstract-painting-i8zEGCKBxQY?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) ![Hero test](static/backgrounds/hero.jpg)"
    design:
      background:
        color:
          light: "primary-50"
          dark: "primary-900"
      spacing:
        padding:
          - "4rem"
          - "0"
          - "4rem"
          - "0"
    ce: "section-about"
    id: "about"
    As: "section-8b735241"

  - block: "features"
    content:
      title: "Our Speakers"
      text: "Meet the experts leading the sessions at our workshop."
      items:
        - name: "Dr. Jane Smith"
          description: "Expert in Computational Biology with 15 years of research experience."
          icon: "academicons/orcid"
        - name: "Prof. John Doe"
          description: "Renowned Data Scientist and author of multiple celebrated papers."
          icon: "academicons/orcid"
        - name: "Dr. Emily Zhang"
          description: "AI Researcher focused on novel machine learning models."
          icon: "academicons/orcid"
    design:
      background:
        color:
          light: "white"
          dark: "slate-900"
      spacing:
        padding:
          - "4rem"
          - "0"
          - "4rem"
          - "0"
    ce: "section-speakers"
    id: "speakers"
    As: "section-30648426"

  - block: workshop-schedule
    id: schedule
    content:
      subtitle: The presentations will be 45 minutes, followed by a discussion of 30 minutes.
      slots:
        - day: Wednesday
          date: 18 December
          time: "9:00 – 10:15"
          speakers:
            - name: Gert de Cooman
              avatar: me.png
              affiliation: University of Bristol
          talks:
            - title: Foundations of Imprecise Probability
              links:
                - label: slides
                  url: /uploads/doe-slides.pdf
              abstract: |
                In this talk, we explore the foundations of imprecise probability and lower/upper previsions.
        - day: Wednesday
          date: 18 December
          time: "9:00 – 10:15"
          speakers:
            - name: Jane Doe
              affiliation: University of Bristol
          talks:
            - title: Foundations of Imprecise Probability
              links:
                - label: slides
                  url: /uploads/doe-slides.pdf
              abstract: |
                In this talk, we explore the foundations of imprecise probability and lower/upper previsions.    
        # (Additional multi-speaker and split session slots can be added following 
---
