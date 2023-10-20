---
# Leave the homepage title empty to use the site title
title:
date: 2023-09-27
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: features
  #   content:
  #     title: Skills
  #     items:
  #       - name: R
  #         description: 90%
  #         icon: r-project
  #         icon_pack: fab
  #       - name: Statistics
  #         description: 100%
  #         icon: chart-line
  #         icon_pack: fas
  #       - name: Photography
  #         description: 10%
  #         icon: camera-retro
  #         icon_pack: fas
  - block: experience
    id: experience
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
        - title: Graduate Research Assistant
          company: ETH Zurich
          company_url: 'https://iip.ethz.ch/'
          company_logo: eth
          location: Zurich, Switzerland
          date_start: '2020-10-01'
          date_end: ''
          description: |2-
              Research on resource allocation for beyond-fifth-generation (B5G) wireless communication systems.
        - title: Graduate Teaching Assistant
          company: ETH Zurich
          company_url: 'https://iip.ethz.ch/'
          company_logo: eth
          location: Zurich, Switzerland
          date_start: '2022-02-22'
          date_end: ''
          description: |2-
              Teaching Assistant for the master’s level lecture Wireless Communications.
        - title: Graduate Research Assistant
          company: Pontifical Catholic University of Rio de Janeiro
          company_url: 'https://www.puc-rio.br/english/'
          company_logo: puc_rio
          location: Rio de Janeiro, Brazil
          date_start: '2018-08-13'
          date_end: '2020-08-21'
          description: |2-
              Research on resource allocation for Cell-Free Massive MIMO Systems. Development of an MMSE precoder with power allocation and antenna selection. Exploration of robust techniques and development of adaptive algorithms. Use of Matlab and CVX.
        - title: Undergraduate Research Assistant
          company: Pontifical Catholic University of Rio de Janeiro
          company_url: 'https://www.puc-rio.br/english/'
          company_logo: puc_rio
          location: Rio de Janeiro, Brazil
          date_start: '2017-08-01'
          date_end: '2018-08-01'
          description: |2-
              Design of an RF amplifier for inductive coupling coils. The project involves design using the software Advanced Design System (ADS) e experiments using metamaterials, with the intent to increase the transmission distance. Participation in the foundation of the Metamaterials Brazilian Society (SBMETA).
        - title: Microwave Intern
          company: Huawei Technologies
          company_url: 'https://www.huawei.com/br/'
          company_logo: huawei
          location: Rio de Janeiro, Brazil
          date_start: '2016-10-01'
          date_end: '2017-08-01'
          description: |2-
              Large communication network planning. Worked with line-of-sight (LOS) simulations for microwave planning and antennas and equipment choices. Had contact with clients such as TIM Brazil and Claro.
        - title: Summer Research Assistant
          company: Huawei Technologies
          company_url: 'https://uci.edu/'
          company_logo: uci
          location: Irvine, United States
          date_start: '2016-05-20'
          date_end: '2016-08-14'
          description: |2-
              Interface development for Parrot AR Drone 2.0 Quadcopter and Turtlebot to work under ROS operational system. An algorithm using Kinect for distance analysis and collision avoidance.
        - title: Portuguese Teacher 
          company: Huawei Technologies
          company_url: 'https://www.uccs.edu/'
          company_logo: uccs
          location: Colorado Springs, United States
          date_start: '2016-03-01'
          date_end: '2016-05-01'
          description: |2-
              Portuguese teacher for american students preparing for summer research in Portugal.
        - title: Undergraduate Research Assistant
          company: Pontifical Catholic University of Rio de Janeiro
          company_url: 'https://www.puc-rio.br/english/'
          company_logo: puc_rio
          location: Rio de Janeiro, Brazil
          date_start: '2014-08-01'
          date_end: '2015-08-01'
          description: |2-
              Development of an app capable of performing Libras (Brazilian Sign Language) to Portuguese and Portuguese to Libras translation, for Android, Windows Phone, and iOS platforms. Worked with databases and web development. Presented a paper at the International Workshop on Assistive Technology, in February 2015.
        - title: Electronics Team Member
          company: Pontifical Catholic University of Rio de Janeiro
          company_url: 'https://www.riobotz.com/'
          company_logo: riobotz
          location: Rio de Janeiro, Brazil
          date_start: '2013-08-01'
          date_end: '2015-08-01'
          description: |2-
              Development and maintenance of the electronics for combat robots that compete at national and international levels. Tasks included soldering, electronic components maintenance, and programming. Gave soldering workshops for new members of the team. Work with DC motors, batteries, speed controllers, and radios. Participation in 3 national competitions (Ultimate Robot Combat 2014, Winter Challenge 2014, Ultimate Robot Combat 2015) and one international (Robogames 2015).
    design:
      columns: '2'
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Awards'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://google.com/
          date_end: ''
          date_start: '2023-01-01'
          description: 'First achievement'
          organization: Department
          organization_url: https://google.com/
          title: First title
          url: 'https://google.com/'
    design:
      columns: '2'

  - block: collection
    id: publications
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      email: palhares@iis.ee.ethz
      contact_links:

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
