---
date: "2024-05-01"
sections:
- block: hero
  content:
#    cta: 
#      label: ''
#      url: 
#    cta_alt:
#      label: 
#      url: 
#    cta_note:
#      label: '<div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder"
#        data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star
#        Hugo Blox Builder</a></div><div style="text-shadow: none;"><a class="github-button"
#        href="https://github.com/HugoBlox/theme-academic-cv" data-icon="octicon-star"
#        data-size="large" data-show-count="true" aria-label="Star">Star the Academic
#        template</a></div>'
    image:
      filename:
    text: |-
      <img src="./cover_landscape.png">

#      <!--Custom spacing-->
#      <div class="mb-3"></div>
#      <!--GitHub Button JS-->
#      <script async defer src="https://buttons.github.io/buttons.js"></script>
    title: 
  demo: false
  design:
    background:
      gradient_end: 'black'
      gradient_start: 'black'
      text_color_light: true
- block: about.biography
  content:
    title: Biography
    username: admin
  id: about
- block: skills
  content:
    text: ""
    title: Skills
    username: admin
  design:
    columns: "1"
#- block: experience
#  content:
#    date_format: Jan 2006
#    items:
#    - company: GenCoin
#      company_logo: org-gc
#      company_url: ""
#      date_end: ""
#      date_start: "2021-01-01"
#      description: |2-
#          Responsibilities include:
#
#          * Analysing
#          * Modelling
#          * Deploying
#      location: California
#      title: CEO
#    - company: University X
#      company_logo: org-x
#      company_url: ""
#      date_end: "2020-12-31"
#      date_start: "2016-01-01"
#      description: Taught electronic engineering and researched semiconductor physics.
#      location: California
#      title: Professor of Semiconductor Physics
#    title: Experience
#  design:
#    columns: "2"
#- block: accomplishments
#  content:
#    date_format: Jan 2006
#    items:
#    - certificate_url: https://www.coursera.org
#      date_end: ""
#      date_start: "2021-01-25"
#      description: ""
#      icon: coursera
#      organization: Coursera
#      organization_url: https://www.coursera.org
#      title: Neural Networks and Deep Learning
#      url: ""
#    - certificate_url: https://www.edx.org
#      date_end: ""
#      date_start: "2021-01-01"
#      description: Formulated informed blockchain models, hypotheses, and use cases.
#      icon: edx
#      organization: edX
#      organization_url: https://www.edx.org
#      title: Blockchain Fundamentals
#      url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#    - certificate_url: https://www.datacamp.com
#      date_end: "2020-12-21"
#      date_start: "2020-07-01"
#      description: ""
#      icon: datacamp
#      organization: DataCamp
#      organization_url: https://www.datacamp.com
#      title: Object-Oriented Programming in R
#      url: ""
#    subtitle: null
#    title: Accomplish&shy;ments
#  design:
#    columns: "2"
#- block: collection
#  content:
#    count: 5
#    filters:
#      author: ""
#      category: ""
#      exclude_featured: false
#      exclude_future: false
#      exclude_past: false
#      folders:
#      - post
#      publication_type: ""
#      tag: ""
#    offset: 0
#    order: desc
#    subtitle: ""
#    text: ""
#    title: Recent Posts
#  design:
#    columns: "2"
#    view: compact
#  id: posts
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Projects
      tag: Data Science
    - name: Featured publications
      tag: Article
    - name: News
      tag: Media
#    - name: Other
#      tag: Demo
#    default_button_index: 0
#    filters:
#      folders:
#      - project
    title: Portfolio
  design:
    columns: "1"
#    flip_alt_rows: false
#    view: showcase
  id: portfolio
#- block: markdown
#  content:
#    subtitle: ""
#    text: |-
#
#      <center><img src = "./project/Beyond Microsoft/imgs/funny-pic.jpg" width = 300 height = 300/>&#nbsp;<img src = "./project/Beyond Microsoft/imgs/gif-gallery.gif" width = 300 height = 300/></center#>
#
#    text: '{{< gallery album="demo" >}}'
#    title: Gallery
#  design:
#    columns: "1"
#- block: collection
#  content:
#    filters:
#      featured_only: true
#      folders:
#      - publication
#    title: Featured Publications
#  design:
#    columns: "2"
#    view: card
#  id: featured
#- block: collection
#  content:
#    filters:
#      exclude_featured: true
#      folders:
#      - publication
#    text: |-
#      {{% callout note %}}
#      Quickly discover relevant content by [filtering publications](./publication/).
#      {{% /callout %}}
#    title: Recent Publications
#  design:
#    columns: "2"
#    view: citation
#- block: collection
#  content:
#    filters:
#      folders:
#      - event
#    title: Recent & Upcoming Talks
#  design:
#    columns: "2"
#    view: compact
#  id: talks
#- block: tag_cloud
#  content:
#    title: Popular Topics
#  design:
#    columns: "2"
- block: contact
  content:
    address:
      city: Tempe
      country: United States
      country_code: US
      postcode: "85287"
      region: AZ
      street: 427 E Tyler Mall
    coordinates:
      latitude: "33.4197"
      longitude: "-111.9339"
#    directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
    email: dpadil10@asu.edu
#    form:
#      formspree:
#        id: null
#      netlify:
#        captcha: false
#      provider: netlify
#    office_hours:
#    - Monday 10:00 to 13:00
#    - Wednesday 09:00 to 10:00
    phone: +1 (480) 646-7769
    subtitle: null
#    text: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis
#      ut magna et, vehicula efficitur enim.
#    title: Contact
  design:
    columns: "2"
  id: contact
title: ""
type: landing
---
