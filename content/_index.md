---
date: "2022-10-24"
sections:

- block: about.biography
  content:
    title: Hi, my name is Admir!
    username: admin
  id: about
  
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Species Distribution Models (SDM)
      tag: SDM
    - name: Machine Learning
      tag: Machine Learning
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects  

- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: GenCoin
      company_logo: org-gc
      company_url: ""
      date_end: ""
      date_start: "2021-01-01"
      description: |2-
          Responsibilities include:

          * Analysing
          * Modelling
          * Deploying
      location: California
      title: CEO
    - company: University X
      company_logo: org-x
      company_url: ""
      date_end: "2020-12-31"
      date_start: "2016-01-01"
      description: Taught electronic engineering and researched semiconductor physics.
      location: California
      title: Professor of Semiconductor Physics
    title: Experience
  design:
    columns: "2"
    
- block: accomplishments
  content:
    date_format: Jan 2006
    items:
    - certificate_url: https://www.coursera.org
      date_end: ""
      date_start: "2021-01-25"
      description: ""
      organization: Coursera
      organization_url: https://www.coursera.org
      title: Neural Networks and Deep Learning
      url: ""
    - certificate_url: https://www.edx.org
      date_end: ""
      date_start: "2021-01-01"
      description: Formulated informed blockchain models, hypotheses, and use cases.
      organization: edX
      organization_url: https://www.edx.org
      title: Blockchain Fundamentals
      url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
    - certificate_url: https://www.datacamp.com
      date_end: "2020-12-21"
      date_start: "2020-07-01"
      description: ""
      organization: DataCamp
      organization_url: https://www.datacamp.com
      title: Object-Oriented Programming in R
      url: ""
    subtitle: null
    title: Accomplish&shy;ments
  design:
    columns: "2"
    
- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Recent Posts
  design:
    columns: "2"
    view: compact
  id: posts
    
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: "2"
    view: card
  id: featured
  
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Recent Publications
  design:
    columns: "2"
    view: citation

- block: tag_cloud
  content:
    title: Popular Topics
  design:
    columns: "2"
    
- block: contact
  content:
    address:
      city: Foz do Iguaçu
      country: Brazil
      country_code: BR
      postcode: "85870-650"
      region: PR
      street: 1000 Tarquínio Joslin dos Santos Avenue
    appointment_url: 
    autolink: true
    contact_links:

    directions: Federal University of Latin-american Integration, JU Campus, Biodiversity Laboratory
    email: admircjunior@gmail.com
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify
    office_hours:
    phone: 
    subtitle: null
    text: Feel free to send me an email, I will respond as soon as possible.
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
