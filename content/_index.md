---
# Leave the homepage title empty to use the site title
title: home
date: 2022-10-24
type: landing

sections:

  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: Geospatial
          description: 90%
          icon: globe
          icon_pack: fas
        - name: Microsoft Office
          description: 95%
          icon: microsoft
          icon_pack: fab 
        - name: Python
          description: 75%
          icon: python
          icon_pack: fab
        - name: Curiosity
          description: 100%
          icon: book
          icon_pack: fas
        - name: Biking
          description: 40%
          icon: biking
          icon_pack: fas
        - name: Robotics
          description: 10%
          icon: robot
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
        - title: Geospatial Data Scientist
          company: The Nature Conservancy
          company_url: ''
          company_logo: ''
          location: Home Office
          date_start: '2021-11-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Geospatial analyses considering EO Big Data
              * Functional connectivity layer (potential) to Pará State
              * EO time series to qualify restoration projects (GEE back-end).
        - title: Data Scientist
          company: BTG Pactual
          company_url: ''
          company_logo: '' 
          location: Home Office
          date_start: '2021-05-01'
          date_end: '2021-10-30'
          description: |2-
              Responsibilities include:

              Providing services to BTG Pactual, Agricultural Insurance.
              Development of spatial analysis/remote sensing technologies to support Underwriting and Claims sectors.
              Languages/stack: Python, Google Earth Engine, Geopandas, and Fiona
        - title: Geospatial Developer
          company: Funcate/INPE
          company_url: ''
          company_logo: '' 
          location: São José dos Campos
          date_start: '2020-08-01'
          date_end: '2021-04-30'
          description: |2-
              Responsibilities include:

              Analysis of radiometric and geometric characteristics of Sentinel-2, Landsat-8, CBERS-4, and CBERS-4A data cubes, data quality, and proposal for improving pre-processing steps.

              Project page: http://brazildatacube.org/
        - title: Data Quality Assessment - Associate Researcher
          company: INPE
          company_url: ''
          company_logo: '' 
          location: São José dos Campos
          date_start: '2020-02-01'
          date_end: '2021-07-30'
          description: |2-
              Responsibilities include:

              Analysis of radiometric and geometric characteristics of Sentinel-2, Landsat-8, CBERS-4, and CBERS-4A data cubes, data quality, and proposal for improving pre-processing steps.

              Project page: http://brazildatacube.org/
        - title: Associate Founder - Product Owner
          company: Nitentech
          company_url: ''
          company_logo: '' 
          location: São José dos Campos
          date_start: '2019-01-01'
          date_end: '2020-07-31'
          description: |2-
              Responsibilities include:

              Analysis of radiometric and geometric characteristics of Sentinel-2, Landsat-8, CBERS-4, and CBERS-4A data cubes, data quality, and proposal for improving pre-processing steps.

              Project page: http://brazildatacube.org/
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Neural Networks and Deep Learning
          url: ''
        - certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2021-01-01'
          description: Formulated informed blockchain models, hypotheses, and use cases.
          organization: edX
          organization_url: https://www.edx.org
          title: Blockchain Fundamentals
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Object-Oriented Programming in R'
          url: ''
    design:
      columns: '2'
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
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
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
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contato
      subtitle:
      text: |-
        Caso queira entrar em contato, envie um e-mail ou utilize algum recurso indicado abaixo.
      # Contact (add or remove contact options as necessary)
      email: guilherme.fronza@gmail.com
      phone: 48 9 88273742
      appointment_url: 'https://calendly.com'
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
