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
      text: "A two-day workshop on the intersections of quantum foundations and formal epistemology at the University of Bristol, April 1-2, 2027."
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
            brightness: 0.4  # Dims the image slightly so text pops
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
      text: |
        #### *How do we become confident in claims about things too small to see?*
        #### *How might the behavior of those exotic things alter our approach to uncertain reasoning?*
        
        Careful attention to the role of probability in quantum foundations has profound implications for both of these questions. This workshop collects a diverse group of physicists and philosophers who have given them novel answers in recent years, covering topics including:
        - the relationship between quantum probabilities and dynamical symmetries;
        - how quantum probabilities inform ontology;
        - how they suggest modifications of formal and/or general epistemology; and 
        - how they improve models of human memory.

        This workshop is the capstone event of Jer Steeger's project [Credence and Chance in a Pluralist Approach to Quantum Theories](https://jsteeger.github.io/projects/credence-chance/) and is generously supported by the British Academy under Grant No. IF23\100451.
    design:
      background:
        color:
          light: "primary-50"
          dark: "primary-900"
      spacing:
        padding:
          - "4rem"
          - "0"
          - "0rem"
          - "0"
    ce: "section-about"
    id: "about"
    As: "section-8b735241"

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
            - name: John Smith
          talks:
            - title: Foundations of Imprecise Probability
              links:
                - label: slides
                  url: /uploads/doe-slides.pdf
              abstract: |
                In this talk, we explore the foundations of imprecise probability and lower/upper previsions.
---
