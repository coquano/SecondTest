---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: 'IMG_20230122_140611_shadow.jpg'
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
    design:
      css_class: bright
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: 'IMG_20230122_140611_shadow.jpg'
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: 'Previous working teams'
      subtitle: ''
      text: |-
        I first worked in the group of Bruno Machet in LPTHE (Laboratoire de Physique Théorique des Hautes Énergies, Sorbonne
        Université, Paris, France) for a couple of months.

        Then, I joined the team of Dominique Mouhanna in LPTMC (Laboratoire de Physique Théorique de la Matière Condensée,
        Sorbonne Université, Paris, France). During this time, I had the chance to collaborate with Sofian Teber from LPTHE (Paris).

        I have been working for three years in the group of Matthias Sperl (Institut für Materialphysik im Weltraum,
        Deutsches Zentrum für Luft- und Raumfahrt, Köln, Germany).

        Before coming to Perpignan, I have worked for one year in the group of Ludovic Berthier in L2C (Laboratoire Charles Coulomb,
        Université de Montpellier, Montpellier, France).

    design:
      columns: '1'
  - block: markdown
    content:
      title: 'Research Interests'
      subtitle: ''
      image:
          # Add your image background to `assets/media/`.
          filename: 'recap.png'
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
      text: |-
        My research interest concentrate on systems that can be considered as holding an intermediate position
        between the two ideal models of the crystalline solid and the simple liquid.
        
        This include for example the study of deformation of crystalline membrane, which, because of their bidemensional character
        present much stronger thermal fluctuations as usual three dimensional solids, and therefore display unconventional elasticity.

        I have also been working on the determination of the structural and rheological properties of complex fluids (that typically
        display non Newtonian rules of flow).

        A quite substantial part of my work has been devoted to the study of the flow properties of granular liquids. These
        systems, despite their ubiquitous character are still poorly understood today because, on the formal level, they escape
        the rules at the basis of the well-known frameworks in statistical physics (the granular particles being dissipative,
        granular flows are always in an out-of-equilibrium state when they are not at rest).

        In order to study these systems, I use a wide combination of tools, mostly from statistical field theory and the renormalisation
        group on the one end (using both perturbative and non perturbative schemes), but also mode-coupling theory

    design:
      columns: '1'
      
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  - block: collection
    id: news
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
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
