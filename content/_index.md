---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Hola
      text: |-
        Welcome to my website! I am an Assistant Professor at the Department of Economics at Southern Methodist University. I am also a CESifo Research Network Affiliate. My research combines income and spending micro-data with quantitative life-cycle and spatial models to answer questions on macroeconomic policy and labor economics; with a particular focus on measuring the propagation and pass-through of income and price changes to individuals' welfare. 
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: publications
    content:
      title: Publications
      # text: |-
      #   {{% callout note %}}
      #   Quickly discover relevant content by [filtering publications](./publication/).
      #   {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
  - block: collection
    id: workingpapers
    content:
      title: Working Papers
      filters:
        folders:
          - workingpapers
    design:
      columns: '2'
      view: citation
  - block: portfolio
    id: workinprogress
    content:
      title: Work in Progress
      filters:
        folders:
          - workinprogress
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: features
    content:
      title: Skills
      items:
        - name: R
          description: 90%
          icon: r-project
          icon_pack: fab
        - name: Matlab
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: Stata
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: Fortran
          description: 100%
          icon: chart-line
          icon_pack: fas
  - block: contact
    id: contact
    content:
      title: Contact
      email: romadera@smu.edu
      # appointment_url: 'https://calendly.com'
      address:
        street: 3300 Dyer Street
        city: Dallas
        region: TX
        postcode: '75205'
        country: United States
        country_code: US
      directions: Office 301V
      office_hours:
        - 'TBA'
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
