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
      # secondary_action:
      #   text: "Learn More"
      #   url: "#schedule"
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
        
        This workshop collects a diverse group of physicists and philosophers who have given these questions novel answers in recent years, covering topics including:
        - how quantum probabilities relate to dynamical symmetries
        - how quantum probabilities inform ontology
        - how quatnum foundations might modify formal and general epistemology 
        - how quantum approaches can improve models of human memory

        This event is organized by [Jer Steeger](https://jsteeger.github.io/) (chair) and [James Read.](https://www.philosophy.ox.ac.uk/people/james-read) It is the capstone event of the project [Credence and Chance in a Pluralist Approach to Quantum Theories,](https://jsteeger.github.io/projects/credence-chance/) which is generously supported by the British Academy under Grant No. IF23\100451.
    design:
      layout: "full"
      background:
        color:
          light: "primary-50"
          dark: "primary-900"
      spacing:
        padding:
          - "4rem"
          - "0rem"
          - "0rem"
          - "0rem"
      css_class: "max-w-5xl mx-auto my-4"
    ce: "section-about"
    id: "about"
    As: "section-8b735241"

  - block: workshop-schedule
    id: day-1
    design:
      spacing:
        padding:
          - "2rem"
          - "0"
          - "0rem"
          - "0"
    content:
      title: Day 1 Talks
      # subtitle: Each presentation will be 40 minutes and followed by a discussion of 35 minutes.
      slots:
        - day: Thursday
          date: 1 April
          time: "9:00 – 10:15"
          speakers:
            - name: Emily Adlam
              # avatar: emily-adlam.jpg
              affiliation: Chapman University
          talks:
            - title: TBA
              # links:
              #   - label: slides
              #     url: /uploads/doe-slides.pdf
              # abstract: |
              #   In this talk, we explore the foundations of imprecise probability and lower/upper previsions.
        - day: Thursday
          date: 1 April
          time: "10:30 – 11:45"
          speakers:
            - name: Jacob Barandes
              # avatar: jacob-barandes.png
              affiliation: Harvard University
          talks:
            - title: TBA
              # links:
              #   - label: slides
              #     url: /uploads/doe-slides.pdf
              # abstract: |
              #   In this talk, we explore the foundations of imprecise probability and lower/upper previsions.
        - day: Thursday
          date: 1 April
          time: "13:00 – 14:15"
          speakers:
            - name: Nadia Blackshaw
              # avatar: nadia-blackshaw.webp
              affiliation: London School of Economics
          talks:
            - title: TBA
              # links:
              #   - label: slides
              #     url: /uploads/doe-slides.pdf
              # abstract: |
              #   In this talk, we explore the foundations of imprecise probability and lower/upper previsions.
        - day: Thursday
          date: 1 April
          time: "14:15 – 15:30"
          speakers:
            - name: Keano De Vos
              # avatar: blank.jpg
              affiliation: University of Gent
            - name: Gert De Cooman
              # avatar: gert-de-cooman.webp
              affiliation: University of Gent
          talks:
            - title: TBA
              # links:
              #   - label: slides
              #     url: /uploads/doe-slides.pdf
              # abstract: |
              #   In this talk, we explore the foundations of imprecise probability and lower/upper previsions.
        - day: Thursday
          date: 1 April
          time: "15:45 – 17:00"
          speakers:
            - name: Fay Dowker
              # avatar: fay-dowker.webp
              affiliation: Imperial College London
          talks:
            - title: TBA
              # links:
              #   - label: slides
              #     url: /uploads/doe-slides.pdf
              # abstract: |
              #   In this talk, we explore the foundations of imprecise probability and lower/upper previsions.

  - block: workshop-schedule
    id: day-2
    design:
      spacing:
        padding:
          - "0rem"
          - "0"
          - "2rem"
          - "0"
    content:
      title: Day 2 Talks
      # subtitle: Each presentation will be 40 minutes and followed by a discussion of 35 minutes.
      slots:
        - day: Friday
          date: 2 April
          time: "9:00 – 10:15"
          speakers:
            - name: Henry Groves
              # avatar: henry-groves.jpg
              affiliation: Newcastle University
            - name: Lucia F. Jackson
              # avatar: blank.jpg
              affiliation: Newcastle University
            - name: Barbara-Anne Robertson
              # avatar: barbara-anne-robertson.jpg
              affiliation: Newcastle University
            - name: Jonte Hance
              # avatar: jonte-hance.webp
              affiliation: Newcastle University
          talks:
            - title: Modelling Emotional Memory in Children with Tensor Networks
              links:
                - label: preprint
                  url: https://arxiv.org/html/2606.28470v1
              abstract: |
                We demonstrate how emotional valence influences the order-dependent structure of children’s recognition memory: correct recall of a sequence of emotionally-valenced toys depended not just on the valence of a given toy itself, but also on the valence of the toys shown before and after it. Whilst standard psychological models confirm that order-dependence differs across an event (a set of toys shown in sequence), accuracy is low and the model does not reflect how memory for an emotional object influences others in the set. A classical tensor network model factoring in valence is able to achieve a 77.98% accuracy in modelling the results of the study. While not strictly a “quantum cognition” model, this massive increase in accuracy shows the value of quantum-inspired methods for modelling order-dependent phenomena, such as emotional memory. Further, the task protocol we introduce presents a novel, real-world tool for exploring emotional temporal memory in children for analysis using classical and quantum-like models of cognition.
        - day: Friday
          date: 2 April
          time: "10:30 – 11:45"
          speakers:
            - name: Joanna Luc
              # avatar: joanna-luc.jpg
              affiliation: Jagiellonian University
          talks:
            - title: TBA
              # links:
              #   - label: slides
              #     url: /uploads/doe-slides.pdf
              # abstract: |
              #   In this talk, we explore the foundations of imprecise probability and lower/upper previsions.
        - day: Friday
          date: 2 April
          time: "13:00 – 14:15"
          speakers:
            - name: Ray Pedersen
              # avatar: ray-pedersen.jpg
              affiliation: University of Oxford
          talks:
            - title: TBA
              # links:
              #   - label: slides
              #     url: /uploads/doe-slides.pdf
              # abstract: |
              #   In this talk, we explore the foundations of imprecise probability and lower/upper previsions.
        - day: Friday
          date: 2 April
          time: "14:15 – 15:30"
          speakers:
            - name: Jer Steeger
              # avatar: me.png
              affiliation: University of Bristol
            - name: James Read
              # avatar: james-read.jpg
              affiliation: University of Oxford
          talks:
            - title: TBA
              # links:
              #   - label: slides
              #     url: /uploads/doe-slides.pdf
              # abstract: |
              #   In this talk, we explore the foundations of imprecise probability and lower/upper previsions.
        - day: Friday
          date: 2 April
          time: "15:45 – 17:00"
          speakers:
            - name: Karim Thébault
              # avatar: karim-thebault.jpg
              affiliation: University of Bristol
          talks:
            - title: TBA
              # links:
              #   - label: slides
              #     url: /uploads/doe-slides.pdf
              # abstract: |
              #   In this talk, we explore the foundations of imprecise probability and lower/upper previsions.

  - block: location
    id: location
    design:
      spacing:
        padding:
          - "2rem"
          - "0"
          - "2rem"
          - "0"
    content:
      title: Locations
      zoom: 16
      locations:
        - venue: Arts Complex Lecture Theatre 2
          address: Arts Complex, 11 Woodland Road, BS8 1TB
          lat: 51.460502049235046
          lng: -2.604044903683711
          text: |
            **Main Workshop Venue** — All talks. Coffee and lunch will be provided in the adjacent lobby.
        # - venue: The Carolina Theatre
        #   address: 309 W Morgan St, Durham, NC 27701
        #   lat: 35.9972
        #   lng: -78.9036
        #   text: |
        #     **Workshop Dinner** — Doors open at 6:30 PM, directly across the plaza.
        - venue: Temple Meads Station
          address: Redcliffe, Bristol BS1 6QF
          lat: 51.44980698342558
          lng: -2.580622863958044
          zoom: 15
          text: |
            **Transit Hub** — 40-minute walk from the workshop venue.
---
