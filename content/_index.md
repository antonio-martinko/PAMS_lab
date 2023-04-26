---
date: "2023-04-25"
sections:
- block: about.avatar
  content:
    text: null
    username: admin
  id: about
  
- block: features
  content:
    items:
    - description: physical activity in epidemiological research and clinical intervention studies
      icon: 📏
      icon_pack: emoji
      name: Measuring
    - description: the population level of physical activity
      icon: 🔎
      icon_pack: emoji
      name: Monitoring
    - description: various systematic solutions for monitoring the level of physical activity
      icon: 💡
      icon_pack: emoji
      name: Developing
    title: Focus on physical activity
    
- block: features
  content:
    items:
    - description: MD; PhD in biomedical sciences. Associate Professor in Physical Activity and Health at the Department of Sport and Exercise Medicine at the Faculty of Kinesiology, University of Zagreb, Croatia and Research Associate at the Faculty of Sport, University of Ljubljana, Slovenia. ![Picture of Lab head Assoc. prof. Maroje Sorić](Maroje_Soric.jpg "")
      icon: 
      icon_pack: emoji
      image: 
      name: Maroje Sorić
    - description: Master's degree in Kinesiology and a PhD Candidate at Macquarie University. Her doctoral research is being conducted within the framework of the Cotutelle program agreed between the two universities. She is employed on the Young Researchers’ Career Development Project. <img src="assets/media/albums/members/Petra_Juric.jpg" alt="Picture of Lab member PhD Petra Jurić">
      icon: 
      icon_pack: emoji
      name: Petra Jurić
    - description: Master's degree in Kinesiology and a PhD Candidate at the Faculty of Kinesiology, University of Zagreb, Croatia. He is employed on the Young Researchers’ Career Development Project.
      icon: 
      icon_pack: emoji
      name: Antonio Martinko
    title: Meet the lab
    
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: The European Network for the Support of Development of Systems for Monitoring Physical Fitness of Children and Adolescents (FitBack)
      company_logo:
      company_url: "https://www.fitbackeurope.eu/en-us/"
      date_end: "2022-01-01"
      date_start: "2020-01-01"
      description: |2-
          The main purpose of this project was to support the establishment of physical fitness surveillance programs by a single, multilingual online platform, FitBack, which provides feedback on specific, individual physical fitness outcomes from the Alpha fit test battery. Fitback contains key information for others to establish their own national, regional or local system for monitoring physical fitness in children and adolescents.
      location: 
      title: Erasmus plus SCP - Collaborative Partnerships
    - company: Science and Technology in childhood Obesity Policy (STOP)
      company_logo: 
      company_url: "https://www.stopchildobesity.eu/"
      date_end: "2022-01-01"
      date_start: "2018-01-01"
      description: Over 4.5 years (2018-22), the STOP project has generated scientifically sound, novel and policy-relevant evidence on the factors that have contributed to the spread of childhood obesity in European countries and on the effects of alternative technological and organisational solutions and policy options available to address childhood obesity.
      location: 
      title: Horizon 2020
    - company: Young Researchers’ Career Development Project – Training New Doctoral Students
      company_logo: 
      company_url: "https://hrzz.hr/en/young-researchers/young-researchers-career-development/"
      date_end: ""
      date_start: "2018-01-01"
      description: The goal of the project is to develop an integral and stable programme of funding young researchers at the doctoral and post-doctoral levels. This programme finances the development of scientific careers of young researchers, striving toward continuous education and exchange of knowledge with the ultimate aim of creating a network of scientists whose skills can compete in the international scientific community.
      location: 
      title: Croatian Science Foundation (HRZZ)
    - company: Croatian Longitudinal Study of Physical Activity in Adolescence (CRO-PALS)
      company_logo: 
      company_url: "https://hrzz.hr/en/young-researchers/young-researchers-career-development/"
      date_end: "2020-01-01"
      date_start: "2016-01-01"
      description: This project built on the ongoing longitudinal research that began in 2014, and included 903 students from 14 randomly selected high schools in Zagreb. The results of this project enabled a better understanding of the determinants and moderators of physical activity and sedentary behaviors in young people. It contributed to scientifically based planning of targeted intervention programs for the primary prevention of chronic diseases.
      location: 
      title: Croatian Science Foundation (HRZZ)
    title: Projects
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
  
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Reformat Data
      tag: Deep Learning
    - name: Other
      tag: Demo
    default_button_index: 0
    filters:
      folders:
      - tools
    title: Tools
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
  
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
      city: Zagreb
      country: Croatia
      country_code: CRO
      postcode: "10 000 Croatia"
      street: Horvacanski zavoj 15
    autolink: true
    contact_links:
    directions: Enter Faculty of Kinesiology, University of Zagreb and take the stairs, turn right, pass towards the boat and make your way towards the Diagnostics laboratory, before reaching the stairs look to the right and there you will see the  PAMS lab (Office 28).
    email: maroje.soric@kif.unizg.hr
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify
    office_hours:
    - Consultations as scheduled through e-mail.
    subtitle: null
    text: Contact us here if you have any questions.
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
