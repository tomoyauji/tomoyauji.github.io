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
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: small # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  # - block: markdown
  #   content:
  #     title: '📚 My Research'
  #     subtitle: ''
  #     text: |-
  #       I am a theoretical physicist working on QCD.
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: papers
  #   content:
  #     title: Selected Publications
  #     filters:
  #       folders:
  #         - publications
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  # - block: collection
  #   id: papers
  #   content:
  #     title: Publications
  #     text: ''
  #     filters:
  #       folders:
  #         - publications
  #       exclude_featured: false
  #   design:
  #     view: citation
  - block: markdown
    id: papers
    content:
      title: Publications
      text: |-
        ## Article

        1. "Photon polarization tensor at finite temperature and density in a magnetic field"<br> Kenji Fukushima, Yoshimasa Hidaka, Tomoya Uji<br> [_JHEP_ **05** (2025) 181](https://doi.org/10.1007/JHEP05(2025)181), [arXiv:2411.09994 [hep-ph]](https://arxiv.org/abs/2411.09994)

        2. "Pseudogauge ambiguity in the distributions of energy density, pressure, and shear force inside the nucleon"<br> Kenji Fukushima, Tomoya Uji<br> [_Phys.Rev.D_ **113** (2026) 1, 016025](https://doi.org/10.1103/mkyh-n8st), [arXiv:2509.10223 [hep-ph]](https://arxiv.org/abs/2509.10223)

        3. "Magnetic-type Love number differentiating quark stars from neutron stars"<br> Kenji Fukushima, Josuke Minamiguchi, Tomoya Uji<br> [arXiv:2511.02236 [astro-ph.HE]](https://arxiv.org/abs/2511.02236)

        4. "Energy-momentum tensor form factors and spin density distribution in the nucleon calculated in a quantized Skyrme model with vector mesons"<br> Kenji Fukushima, Tomoya Uji<br> [arXiv:2603.11704 [hep-ph]](https://arxiv.org/abs/2603.11704)

        
  # - block: markdown
  #   id: talks
  #   content:
  #     title: Talks
  #     text: |-
  #       ## Article

  #       1. "Photon polarization tensor at finite temperature and density in a magnetic field"<br> Kenji Fukushima, Yoshimasa Hidaka, Tomoya Uji<br> [_JHEP_ **05** (2025) 181](https://doi.org/10.1007/JHEP05(2025)181), [arXiv:2411.09994 [hep-ph]](https://arxiv.org/abs/2411.09994)

  #       2. "Pseudogauge ambiguity in the distributions of energy density, pressure, and shear force inside the nucleon"<br> Kenji Fukushima, Tomoya Uji<br> [_Phys.Rev.D_ **113** (2026) 1, 016025](https://doi.org/10.1103/mkyh-n8st), [arXiv:2509.10223 [hep-ph]](https://arxiv.org/abs/2509.10223)

  #       3. "Magnetic-type Love number differentiating quark stars from neutron stars"<br> Kenji Fukushima, Josuke Minamiguchi, Tomoya Uji<br> [arXiv:2511.02236 [astro-ph.HE]](https://arxiv.org/abs/2511.02236)

  #       4. "Energy-momentum tensor form factors and spin density distribution in the nucleon calculated in a quantized Skyrme model with vector mesons"<br> Kenji Fukushima, Tomoya Uji<br> [arXiv:2603.11704 [hep-ph]](https://arxiv.org/abs/2603.11704)

  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: blog
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 10
  #     # Filter on criteria
  #     filters:
  #       author: ''
  #       category: ''
  #       tag: ''
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ''
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: card
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  # - block: cta-card
  #   demo: true # Only display this section in the HugoBlox Kit demo site
  #   content:
  #     title: 👉 Build your own academic website like this
  #     text: |-
  #       This site is generated by HugoBlox Kit - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

  #       <a class="github-button" href="https://github.com/HugoBlox/kit" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/kit on GitHub">Star</a>

  #       Easily build anything with blocks - no-code required!

  #       From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: 'bg-primary-300 dark:bg-primary-700'
  #       css_style: ''
---
