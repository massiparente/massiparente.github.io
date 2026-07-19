---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
        summary: ''
        experience: ''
        bio: ''
    design:
      background:
        image:
          filename: background.jpg
          filters:
            brightness: 0.6
          size: cover
          position: center
          parallax: false
        text_color_light: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: large # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded

  - block: markdown
    content:
      title: My Research
      text: |-
        I study how galaxies form and evolve across cosmic time using cosmological hydrodynamic simulations and semi-analytic models. A central theme of my research is the role of the interstellar medium — and in particular **cosmic dust** and **polycyclic aromatic hydrocarbons (PAHs)** — in shaping galaxy properties and their observational signatures.

        Both dust and PAHs absorb and reprocess stellar light, so the light we collect when we observe galaxies has been fundamentally reshaped by these components. I build and run models to understand what information this light encodes about the physical state of galaxies — and to interpret what the most powerful telescopes on Earth and in space, like ALMA and JWST, can reveal about them.

        Interested in my research or want to use my models? Feel free to reach out!
    design:
      columns: '2'

  - block: collection
    id: science
    content:
      title: Science
      filters:
        folders:
          - research
    design:
      view: card
      columns: 2
  - block: collection
    id: papers
    content:
      title: Selected Publications
      text: '<a href="https://ui.adsabs.harvard.edu/search/q=orcid%3A0000-0002-9729-3721&sort=date%20desc%2C%20bibcode%20desc&p_=0" target="_blank" rel="noopener" class="ads-btn">View full publication list on NASA ADS ↗</a>'
      count: 0
      filters:
        folders:
          - publications
    design:
      view: citation
  - block: markdown
    id: talks
    content:
      title: Talks & Seminars
      text: |-
        <img src="/media/talk_japan.png" alt="Talk in Japan" style="max-width: 100%; margin-bottom: 1.5rem; border-radius: 8px;">


        **2026**
        - Exploring the Aromatic Universe in the JWST era — London, Canada
        - Lunch Talk, ESO - Garching, Germany
        - Invited Seminar - University of Gent, Belgium
        - Invited Seminar - INAF Bologna, Italy
        - The Drivers of Galaxy Evolution through Cosmic Time — Florence, Italy
        - From Dust Till Dawn — Leiden, The Netherlands
        - UF Colloquium — Gainesville, USA

        **2025**
        - L-Galaxies Workshop — Berlin, Germany *(online)*
        - Peering through an Opaque ISM — Ferrara, Italy
        - Hydrosim Collaboration Meeting — Trieste, Italy
        - IR Fine-Structure Lines Workshop — Winona, USA
        - Invited Seminar - University of Florida, Gainesville, USA

        **2024**
        - Evolution of Dust and Gas throughout Cosmic Time — Hiroshima, Japan
        - The Origin and Evolution of SMBHs — Sexten, Italy
        - Hydrosim Collaboration Meeting — Ljubljana, Slovenia
        - Bridging Models and Observations of Galaxies Dust in the JWST Era — IFPU Trieste, Italy
        - L-Galaxies Workshop — Donostia, Spain

        **2023**
        - 4th Regional Extragalactic Astronomy Meeting — Córdoba, Argentina
        - Invited Seminar - IATE Córdoba, Argentina
        - Origin and Fate of Dust in Our Universe — Gothenburg, Sweden
        - IFPU Focus Week: Galactic Archeology — Trieste, Italy
        - Cosmology 2023 in Miramare — Trieste, Italy
        - Invited Seminar - ICC Durham, UK

        **2021–2022**
        - Invited Seminar - IATE Córdoba *(online)*
        - Hydrosim Collaboration Meetings — Trieste *(online)*

    design:
      columns: '1'
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 10
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the HugoBlox Kit demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by HugoBlox Kit - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/kit" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/kit on GitHub">Star</a>

        Easily build anything with blocks - no-code required!

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-gradient-to-br from-primary-500 via-primary-600 to-secondary-600 text-white shadow-2xl'
        css_style: ''
---
