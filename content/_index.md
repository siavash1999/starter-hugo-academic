---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-01-29
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'

  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Mechanical Designer
          company: ISENSE Co.
          company_url: 'http://isenseco.com'
          company_logo: isense_logo
          location: Tehran, Iran
          date_start: '2022-07-23'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Vibration Analysis
              * Electronic Circuit Analysis
              * CAD Modeling

        - title: Voluntary Member
          company: Student Scientific Society (SSS) of Mechanical Engineering, IUST
          company_url: ''
          company_logo: ssme_logo
          location: Tehran, Iran
          date_start: '2018-01-01'
          date_end: '2022-07-01'
          description: |2-
              * Managed Classes
              * Tutored a Simulink Workshop
              * Designed Questions for Matlab Competition
              * Conducted a MATLAB course

        - title: Member of Editorial Board
          company: Takane Magazine
          company_url: ''
          company_logo: ''
          location: Tehran, Iran
          date_start: '2018-01-01'
          date_end: '2022-07-01'
          description: ''

        - title: Official Member
          company: Language Institute and Cultural Center, IUST
          company_url: ''
          company_logo: licc_logo
          location: Tehran, Iran
          date_start: '2018-01-01'
          date_end: '2020-01-01'
          description: ''

        - title: Teaching Assistant
          company: Mechanical Engineering Department, IUST
          company_logo: iust_logo
          location: Tehran, Iran
          date_start: '2020-09-01'
          date_end: '2020-12-01'
          description: Dynamic Course


        - title: Teaching Assistant
          company: Mechanical Engineering Department, IUST
          company_logo: iust_logo
          location: Tehran, Iran
          date_start: '2020-01-01'
          date_end: '2020-03-01'
          description: Vibration Course
    design:
      columns: '2'

  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Certificates'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: 'Supervised Machine Learning: Regression and Classification'
          date_start: '2022-08-05'
          date_end: ''
          organization: Coursera
          organization_url: https://coursera.org
          certificate_url: "https://coursera.org/verify/M5L237ZXTCJ9"
          description: ''
          
          
          url: ''

        - title: Advanced Python Programming and Object-Oriented Thinking Course
          date_start: '2020-04-01'
          organization: Quera College
          organization_url: https://www.quera.org
          certificate_url: "uploads/quera_advanced_python.jpg"

        - title: Task-Oriented Course in Fundamentals of Python Programming and Algorithmic Thinking
          date_start: '2020-03-01'
          organization: Quera College
          organization_url: https://www.quera.org/
          certificate_url: "uploads/quera_beginner_python.jpg"
          

        - title: 'Bayesian Signal and Image Processing with Application on Vibration and Acoustics'
          date_start: '2020-02-18'
          organization: Iranian Society of Acoustics and Vibration
          organization_url: http://isav.ir/
          certificate_url: ''

        - title: 'Abaqus Course'
          date_start: '2019-05-29'
          organization: Student Scientific Society of Mechanical Engineering
          organization_url: http://mech.iust.ac.ir/student-affairs/#student-scientific-affairs-office
          certificate_url: ''

        - title: 'Beginner Solidworks Course'
          date_start: '2018-08-26'
          organization: Student Scientific Society of Mechanical Engineering
          organization_url: http://mech.iust.ac.ir/student-affairs/#student-scientific-affairs-office
          certificate_url: ''

        - title: 'Beginner Matlab Course'
          date_start: '2018-08-26'
          organization: Student Scientific Society of Mechanical Engineering
          organization_url: http://mech.iust.ac.ir/student-affairs/#student-scientific-affairs-office
          certificate_url: ''

        - title: 'Electrotechnic Course and workshop'
          date_start: '2018-03-08'
          organization: Tehran Institute of Technology
          organization_url: https://mftplus.com/
          certificate_url: ''
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
        - name: Course Projects
          tag: course
        - name: Hobby Projects
          tag: hobby
        - name: Others
          tag: others
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
      text: ''
      email: siaemam@gmail.com
      phone: '+98 912 0039 440'
      address:
        street: 8 Babaei, Fayyaz
        city: Tehran
        region: Sattarkhan
        postcode: ''
        country: Iran
        country_code: IR
      coordinates:
        latitude: ''
        longitude: ''
      directions: ''
      office_hours: ''
      appointment_url: ''
      contact_links:
        - icon: telegram
          icon_pack: fab
          name: Telegram
          link: 'https://t.me/SIA1999'
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
