---
date: "2022-10-24"
sections:
- block: about.avatar
  content:
    text: null
    username: admin
  id: about
- block: features
  content:
    items:
    - description: Import, Clean, Analyze and Visualize data | R Markdown | Dashboards | Shiny apps
      icon: r-project
      icon_pack: fab
      name: Data Science in R
    - description: Descriptive | Inferential | Predictive
      icon: chart-line
      icon_pack: fas
      name: Statistics
    - description: Documents | Slides with Beamer
      icon: edit
      icon_pack: fas
      name: LaTeX
    title: Skills
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: Universidad de Lima
      #company_logo: org-gc
      company_url: "https://www.ulima.edu.pe"
      date_end: ""
      date_start: "2019-04-01"
      description: |2-
          I teach **Applied Statistics** and I am the **Course Coordinator** of this undergraduate course in the Systems Engineering School. I also taught the first and second course of Statistics and Probability.
          
      location: Lima, Peru
      title: Lecturer
    - company: Pontificia Universidad Católica del Perú (PUCP)
      #company_logo: org-x
      company_url: "https://www.pucp.edu.pe"
      date_end: "2021-01-31"
      date_start: "2020-02-14"
      description: I taught **Applied Statistics** in the [Specialization Program in Data Analytics](https://educacioncontinua.pucp.edu.pe/programas/diplomatura-de-especializacion-en-data-analytics/). 
      location: Lima, Peru
      title: Instructor      
      
    - company: National University of Engineering (UNI)
      #company_logo: org-x
      company_url: "https://www.uni.edu.pe"
      date_end: "2018-12-21"
      date_start: "2016-08-22"
      description: I taught the undergraduate courses **Statistics I** and **II**, **Computing II** and **Biostatistics**. I also taught **Data Analysis Introduction** and **Advanced Data Analysis** in the [Specialization Program in Business Intelligence & Business Analytics (PEBIBA)](https://fieecs.uni.edu.pe/business-intelligence-business-analytics/).
      location: Lima, Peru
      title: Lecturer  
    title: Experience
  design:
    columns: "2"
# - block: accomplishments
#   content:
#     date_format: Jan 2006
#     items:
#     - certificate_url: https://www.coursera.org
#       date_end: ""
#       date_start: "2021-01-25"
#       description: ""
#       organization: Coursera
#       organization_url: https://www.coursera.org
#       title: Neural Networks and Deep Learning
#       url: ""
#     - certificate_url: https://www.edx.org
#       date_end: ""
#       date_start: "2021-01-01"
#       description: Formulated informed blockchain models, hypotheses, and use cases.
#       organization: edX
#       organization_url: https://www.edx.org
#       title: Blockchain Fundamentals
#       url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#     - certificate_url: https://www.datacamp.com
#       date_end: "2020-12-21"
#       date_start: "2020-07-01"
#       description: ""
#       organization: DataCamp
#       organization_url: https://www.datacamp.com
#       title: Object-Oriented Programming in R
#       url: ""
#     subtitle: null
#     title: Accomplish&shy;ments
#   design:
#     columns: "2"

# - block: portfolio
#   content:
#     buttons:
#     - name: All
#       tag: '*'
#     - name: Deep Learning
#       tag: Deep Learning
#     - name: Other
#       tag: Demo
#     default_button_index: 0
#     filters:
#       folders:
#       - project
#     title: Projects
#   design:
#     columns: "1"
#     flip_alt_rows: false
#     view: showcase
#   id: projects
  
# - block: markdown
#   content:
#     subtitle: ""
#     text: '{{< gallery album="demo" >}}'
#     title: Gallery
#   design:
#     columns: "1"
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

- block: collection
  content:
    filters:
      # exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Publications
  design:
    columns: "2"
    view: citation
  id: featured

- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: shiny
      tag: shiny
    - name: rmarkdown
      tag: rmarkdown
    default_button_index: 0
    filters:
      folders:
      - workshop
    title: Past Workshops
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: workshops

- block: collection
  content:
    archive:
      enable: true
      text: See all talks
      link: event/
    filters:
      folders:
      - event
    title: Recent & Upcoming Talks
  design:
    columns: "2"
    view: compact
  id: talks

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
  
- block: tag_cloud
  content:
    title: Popular Topics
  design:
    columns: "2"
- block: contact
  content:
    autolink: true
    contact_links:
    - icon: twitter
      icon_pack: fab
      link: https://twitter.com/vilsurr
      name: DM Me
    email: vromeror@uni.pe
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
