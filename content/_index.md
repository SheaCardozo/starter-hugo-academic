---
# Leave the homepage title empty to use the site title
title: Shea Cardozo
date: 2022-12-16
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Education'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_end: 'Ongoing'
          date_start: '2023-09-01'
          description: 'Supervisor: Professor Krzysztof Czarnecki - Waterloo Intelligent Systems Lab'
          organization: University of Waterloo
          organization_url: https://cs.uwaterloo.ca/
          title: PhD in Computer Science
          url: ''
        - date_end: '2022-12-31'
          date_start: '2021-09-01'
          description: 'Data Science Concentration'
          organization: University of Toronto - St. George
          organization_url: https://cs.toronto.edu/
          title: Master of Science in Applied Computing
          url: ''
        - date_end: '2021-06-01'
          date_start: '2017-09-01'
          description:
          organization: University of Waterloo
          organization_url: https://cs.uwaterloo.ca/
          title: Bachelor of Mathematics in Statistics
          url: ''
    design:
      columns: '2'
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
        - title: Machine Learning Scientist
          company: Tenyks
          company_url: 'https://www.tenyks.ai/'
          company_logo: org-tenyks
          location: Cambridge, UK
          date_start: '2022-04-01'
          date_end: ''
          description: |2-
            Working on the Research Team to come up with new data-centric ways to explain and improve Computer Vision systems.
              
        - title: Data Scientist - Claims AI Team
          company: Intact Insurance
          company_url: 'https://www.intact.ca/'
          company_logo: org-intact
          location: Toronto, Canada
          date_start: '2020-09-01'
          date_end: '2020-12-31'
          description: Used Vision and NLP techniques to automatically classify insurance documents.

        - title: Data Scientist - Analytics
          company: Noom Inc.
          company_url: 'https://www.noom.com/'
          company_logo: org-noom
          location: New York City, US
          date_start: '2020-05-01'
          date_end: '2020-08-31'
          description: Improved food and support tracking to streamline internal processes.
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
  #- block: markdown
  #  content:
  #    title: Gallery
  #    subtitle: ''
  #    text: |-
  #      {{< gallery album="demo" >}}
  #  design:
  #    columns: '1'
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
  #- block: collection
  #  content:
  #    title: Recent Publications
  #    text: |-
  #      {{% callout note %}}
  #      Quickly discover relevant content by [filtering publications](./publication/).
  #      {{% /callout %}}
  #    filters:
  #      folders:
  #        - publication
  #      exclude_featured: true
  #  design:
  #    columns: '2'
  #    view: citation
  - block: portfolio
    id: projects
    content:
      title: Featured Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      #default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      #buttons:
      #  - name: All
      #    tag: '*'
      #  - name: Deep Learning
      #    tag: Deep Learning
      #  - name: Other
      #    tag: Demo
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
      # Contact (add or remove contact options as necessary)
      email: shea.cardozo@mail.utoronto.ca
      phone: 1-416-580-3011
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
