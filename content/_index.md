---
# Leave the homepage title empty to use the site title
title: 
date: 2023-07-28
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Short Bio
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
    design:
      background:
        image:
          # Name of image in `assets/media/`.
          filename: 'bg.JPG'
          # Apply image filters?
          filters:
            # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            brightness: 0.4
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
        text_color_light: true
  - block: features
    content:
      title: What I usually do
      items:
        - name: Python
          icon: python
          icon_pack: fab
        - name: Linux
          icon: linux
          icon_pack: fab
        - name: Software-Defined Radio
          icon: radio
          icon_pack: fas
        - name: Signal Processing
          icon: wave-square
          icon_pack: fas
        - name: Robotics
          icon: robot
          icon_pack: fas
        - name: Machine-Learning
          icon: microchip
          icon_pack: fas
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: PhD Student
          company: IMDEA Networks
          company_url: 'networks.imdea.org'
          location: Madrid
          date_start: '2019-06-01'
          date_end: ''
          description: |2-
            Developed and maintained the Electrosense network. Research mostly focused on:
              * Crowdsensing
              * Software-Defined Radio
              * Localization
              * Signal Processing
        - title: Research Assistant
          company: MIT Media Lab
          company_url: 'media.mit.edu'
          location: Boston
          date_start: '2017-09-01'
          date_end: '2018-12-31'
          description: |2-
            Research on lightweight autonomous vehicles. In particular I worked on:
              - Simultaneous Localization and Mapping (SLAM)
              - Obstacle Detection
              - Vehicle UX
        - title: Engineer
          company: JL Ingenieria
          company_url: 'https://www.jlizarribar.es/'
          location: San Sebastian
          date_start: '2017-06-01'
          date_end: '2017-08-31'
          description:
        - title: Engineer
          company: JL Ingenieria
          company_url: 'https://www.jlizarribar.es/'
          location: San Sebastian
          date_start: '2016-06-01'
          date_end: '2016-08-31'
          description: 
        - title: Research Assistant
          company: German Aerospace Center (DLR)
          company_url: 'https://dlr.de'
          location: Munich
          date_start: '2015-06-01'
          date_end: '2015-08-31'
          description: 
    design:
      columns: '2'
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  #   design:
  #     columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
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
      view: compact
      columns: '2'
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Other
  #         tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        ### [View more publications...](./publication/)
      filters:
        folders:
          - publication
        exclude_featured: false
      sort_by: 'Date'
      sort_ascending: false
    design:
      columns: '2'
      view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Contact me if you want to ask me something!
      # Contact (add or remove contact options as necessary)
      email: yago.lizarribar@gmail.com
      address:
        street: Av. Mar Mediterraneo 22
        city: Leganes
        region: Madrid
        postcode: '28918'
        country: Spain
        country_code: ES
      office_hours:
        - 'Monday-Friday 09:00 to 19:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/yagoliz'
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
