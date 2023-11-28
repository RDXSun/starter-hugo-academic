---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Introduction
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: DeepLearning
          description: Grasp PyTorch, TensorFlow, Gensim, Keras, etc.
          icon: brain
          icon_pack: fas
        - name: NLP(LLM/MLLM/NMT/etc.)
          description: Master pre-training and fine-tuning of large language models
          icon: language
          icon_pack: fas
        - name: Computer Vision
          description: 2D, YOLO, nnUNet, Segmentation, Detection, etc.
          icon: glasses
          icon_pack: fas
        - name: full-stack
          description: Independently built both the front-end and back-end for Web and Android platforms
          icon: computer
          icon_pack: fas
        - name: C/C++/Java
          description: Good
          icon: code
          icon_pack: fas
        - name: Python
          description: Master
          icon: python
          icon_pack: fab
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
        - title: Research Assistant
          company: Centre for Artificial Intelligence and Robotics (CAIR) Hong Kong Institute of Science & Innovation, Chinese Academy of Sciences (HKISI-CAS)
          company_url: 'https://www.cair-cas.org.hk'
          company_logo: cair
          location: Hong Kong
          date_start: '2023-10-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Responsible for the research and development of agents specifically designed for the surgical field and related applications. These include Multimodal Large Language Models (MLLM), specialized surgical text-based large language models (LLM), and Retrieval-Augmented Generation (RAG) methods, all aimed at expanding the knowledge boundaries of LLMs.
              * Responsible for conducting research on the segmentation and detection of anatomical structures and surgical instruments in clinical and surgical scenarios, with a primary focus on aiding in the diagnosis of abnormalities and providing surgical assistance.
              * Responsible for formulating technical solutions that integrate various surgical tasks with medical and surgical scenarios. This involves developing adaptive methods that facilitate the transition of downstream tasks across diverse surgical contexts, thereby enhancing procedural efficiency and contributing to the advancement of surgical practices.
        - title: Summer Intern
          company: Centre for Artificial Intelligence and Robotics (CAIR) Hong Kong Institute of Science & Innovation, Chinese Academy of Sciences (HKISI-CAS)
          company_url: 'https://www.cair-cas.org.hk'
          company_logo: cair
          location: Hong Kong
          date_start: '2023-06-27'
          date_end: '2023-08-15'
          description: |2-
              Responsibilities include:

              * Responsible for the development of front-end and back-end web systems for the Surgical Large Language Model.
              * Responsible for the speech and vision modules of the Multimodal Large Language Model.
              * Responsible for keypoints detection of instrumentation in dense scenarios.
      columns: '2'
#  - block: accomplishments
#    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
#      title: 'Accomplish&shy;ments'
#      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
#      items:
#        - certificate_url: https://www.coursera.org
#          date_end: ''
#          date_start: '2021-01-25'
#          description: ''
#          organization: Coursera
#          organization_url: https://www.coursera.org
#          title: Neural Networks and Deep Learning
#          url: ''
#        - certificate_url: https://www.edx.org
#          date_end: ''
#          date_start: '2021-01-01'
#          description: Formulated informed blockchain models, hypotheses, and use cases.
#          organization: edX
#          organization_url: https://www.edx.org
#          title: Blockchain Fundamentals
#          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#        - certificate_url: https://www.datacamp.com
#          date_end: '2020-12-21'
#          date_start: '2020-07-01'
#          description: ''
#          organization: DataCamp
#          organization_url: https://www.datacamp.com
#          title: 'Object-Oriented Programming in R'
#          url: ''
#    design:
#      columns: '2'
#  - block: collection
#    id: posts
#    content:
#      title: Recent Posts
#      subtitle: ''
#      text: ''
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
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
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
#  - block: markdown
#    content:
#      title: Gallery
    #   subtitle: ''
    #   text: |-
    #     {{< gallery album="demo" >}}
    # design:
    #   columns: '1'
#  - block: collection
#    id: featured
#    content:
    #   title: Featured Publications
    #   filters:
    #     folders:
    #       - publication
    #     featured_only: true
    # design:
    #   columns: '2'
    #   view: card
#  - block: collection
#    content:
#      title: Recent Publications
    #   text: |-
    #     {{% callout note %}}
    #     Quickly discover relevant content by [filtering publications](./publication/).
    #     {{% /callout %}}
    #   filters:
    #     folders:
    #       - publication
    #     exclude_featured: true
    # design:
    #   columns: '2'
    #   view: citation
#  - block: collection
#    id: talks
#    content:
    #   title: Recent & Upcoming Talks
    #   filters:
    #     folders:
    #       - event
    # design:
    #   columns: '2'
    #   view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: zhensun26@gmail.com
      phone: 15207702805
      appointment_url: 'https://calendly.com'
      address:
        street: NA
        city: GuangXi
        region: NA
        postcode: '536000'
        country: China
        country_code: China
      directions: NA
      office_hours:
        - always
      contact_links:
        #- icon: twitter
        #  icon_pack: fab
        #  name: DM Me
        #  link: 'https://twitter.com/Twitter'
        #- icon: skype
        #  icon_pack: fab
        #  name: Skype Me
        #  link: 'skype:echo123?call'
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
