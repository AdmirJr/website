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
    - company: Frexco
      company_logo: 
      company_url: ""
      date_end: "2023-03-01"
      date_start: "2022-11-01"
      description: |2-
          Responsibilities include:

          * Analysing
          * Modelling
          * Deploying
      location: São Paulo
      title: Data Science Intern
    - company: Freelance
      company_logo: 
      company_url: ""
      date_end: ""
      date_start: "2021-05-01"
      description: |2-
          Responsibilities include:

          * Data wrangling
          * Statistical consulting
          * Statistical review
      location: 
      title: Statistical Analysis
    - company: Federal University of Latin-american Integration - UNILA
      company_logo:
      company_url: ""
      date_end: ""
      date_start: "2023-03-01"
      description: Master's student, researcher, and CAPES scholarship holder in the postgraduate program at the Federal University of Latin-american Integration.
      title: M.Sc. grant recipient
    title: Experience
  design:
    columns: "2"
    
- block: accomplishments
  content:
    date_format: Jan 2006
    items:
    - certificate_url: https://cursos.alura.com.br/degree/certificate/c3133e8e-10c8-4c64-b974-f35ce9bb2644
      date_end: ""
      date_start: "2023-05-25"
      description: ""
      organization: Alura
      organization_url: https://www.alura.com.br/
      title: Deep Learning with PyTorch
      url: ""
    - certificate_url: https://cursos.alura.com.br/degree/certificate/cc556867-1848-4f0b-baf9-e83009400bd0
      date_end: ""
      date_start: "2022-06-01"
      description: 
      organization: Alura
      organization_url: https://www.alura.com.br/
      title: Statistics with R
      url: 
    - certificate_url: https://cursos.alura.com.br/certificate/7480fedc-b37f-4045-8788-2f7ae8d9cbea
      date_end: ""
      date_start: "2022-07-01"
      description: ""
      organization: Alura
      organization_url: https://www.alura.com.br/
      title: PostgreSQL
      url: ""
    - certificate_url: https://www.udemy.com/certificate/UC-bd95fb88-c7da-4936-b4e1-08635c3fae6e/
      date_end: ""
      date_start: "2022-10-01"
      description: ""
      organization: Udemy
      organization_url: https://www.udemy.com/
      title: QGIS
      url: ""
    subtitle: null
    title: Accomplish&shy;ments
  design:
    columns: "2"
    
# - block: collection
#   content:
#     count: 5
#     filters:
#       author: ""
#       category: ""
#       exclude_featured: false
#       exclude_future: false
#       exclude_past: false
#       folders:
#       - post
#       publication_type: ""
#       tag: ""
#     offset: 0
#     order: desc
#     subtitle: ""
#     text: ""
#     title: Recent Posts
#   design:
#     columns: "2"
#     view: compact
#   id: posts
    
# - block: collection
#   content:
#     filters:
#       featured_only: true
#       folders:
#       - publication
#     title: Featured Publications
#   design:
#     columns: "2"
#     view: card
#   id: featured

# - block: collection
#   content:
#     filters:
#       exclude_featured: true
#       folders:
#       - publication
#     text: |-
#       {{% callout note %}}
#       Quickly discover relevant content by [filtering publications](./publication/).
#       {{% /callout %}}
#     title: Recent Publications
#   design:
#     columns: "2"
#     view: citation

# - block: tag_cloud
#   content:
#     title: Popular Topics
#   design:
#     columns: "2"
    
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
