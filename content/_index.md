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
        - title: Data Science and Innovation Lead
          company: The Nature Conservancy
          company_url: ''
          company_logo: ''
          location: Home Office
          date_start: '2023-10-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * People Management 
              * Innovation Project Proposals
              * Geospatial Governance and Development
              * Digital Innovation Advocate
              * Innovative Data Science Strategist.
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
          location: São José dos Campos-SP
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
          location: São José dos Campos-SP
          date_start: '2021-02-01'
          date_end: '2021-07-30'
          description: |2-
              Responsibilities include:

              Analysis of radiometric and geometric characteristics of Sentinel-2, Landsat-8, CBERS-4, and CBERS-4A data cubes, data quality, and proposal for improving pre-processing steps.

              Project page: http://brazildatacube.org/
        - title: Associate Founder - Product Owner
          company: Nitentech
          company_url: ''
          company_logo: '' 
          location: São José dos Campos-SP
          date_start: '2019-01-01'
          date_end: '2020-07-31'
          description: |2-
              Responsibilities include:

              The Orion Platform allows for complete customization and modularization of data collection and forms by the field/operations team in specific projects or activities, such as archaeology, construction inspection, logistics, dynamic reports, physical environment, environmental inspection, environmental liabilities, field recognition, checklists, control and validation of developed activities, etc.

              The application works on tablets and smartphones and allows for fully offline data collection, providing a spatial and non-spatial database (yes, we have online maps) almost in real-time stored in the cloud, as well as tracking activities through graphs and management dashboards and their multiple outputs (Excel spreadsheets, Google Earth KML, and customized PDF reports for your clients).
        - title: Enviromental Analyst
          company: MRS Ambiental
          company_url: ''
          company_logo: '' 
          location: Brasília-DF
          date_start: '2019-02-01'
          date_end: '2020-02-28'
          description: |2-
              Responsibilities include:

              * Innovation and digital transformation
              * Digital marketing, SEO, growth hacking
              * Implementation of systems and mobile applications
        - title: Product Owner and Consultant
          company: Ambientare - Soluções em Meio Ambiente
          company_url: ''
          company_logo: '' 
          location: Brasília-DF
          date_start: '2017-12-01'
          date_end: '2019-01-31'
          description: |2-
              Responsibilities include:

              * Responsible for the development of SIGA (Integrated Environmental Management System)
              * Semi-automated enviromental reports
              * Developed customized data collection Android mobile application based on specific forms
              * Customized offline environmental data collection geospatial platform
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
        - certificate_url: 
          date_end: ''
          date_start: '2023-01-01'
          description: 'Self-awareness. Motivation. Decision-making.'
          organization: Linkedin
          organization_url: https://www.linkedin.com
          title: Self-Leadership course
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2021-08-01'
          description: TOEFL IBT score 89
          organization: TOEFL
          organization_url: https://www.ets.org/toefl.html
          title: TOEFL Certification
          url: https://www.ets.org/toefl.html
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
        - name: WebGIS
          tag: WebGIS
        - name: Field
          tag: Field
        - name: Remote Sensing
          tag: RemoteSensing
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      #text: |-
        If you want to get in touch, send an email or use one of the resources indicated in this page.
      # Contact (add or remove contact options as necessary)
      email: guilherme.fronza@gmail.com
      phone: 48 9 88273742
      #appointment_url: 'https://calendly.com'
      address:
        street: ''
        city: Florianópolis
        region: SC
        postcode: ''
        country: Brazil
        country_code: BR
    design:
      columns: '2'
---
