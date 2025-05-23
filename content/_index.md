---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
 # - block: hero
  #  content:
   #   title: Hugo Academic Theme
  #    image:
   #     filename: hero-academic.png
  #    cta:
  #      label: '**Get Started**'
  #      url: https://wowchemy.com/templates/
  #   cta_alt:
  #    label: Ask a question
  #   url: https://discord.gg/z8wNYzb
  #   cta_note:
   #   label: >-
   #     <div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/wowchemy-hugo-themes" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Wowchemy Website Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/starter-hugo-academic" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
  # text: |-
  #    **Generated by Wowchemy - the FREE, Hugo-based open source website builder trusted by 500,000+ sites.**

  #   **Easily build anything with blocks - no-code required!**

  #  From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.

   #     <!--Custom spacing-->
   #     <div class="mb-3"></div>
 #       <!--GitHub Button JS-->
 #       <script async defer src="https://buttons.github.io/buttons.js"></script>
#  design:
 #     background:
 #       gradient_end: '#1976d2'
 #       gradient_start: '#004ba0'
  #      text_color_light: true
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
 # - block: features
  #   content:
   #    title: Skills
   #    items:
   #      - name: R
  #          description: 90%
 #           icon: r-project
 #          icon_pack: fab
 #        - name: Statistics
 #          description: 100%
  #         icon: chart-line
 #          icon_pack: fas
  #       - name: Photography
  #         description: 10%
  #         icon: camera-retro
   #        icon_pack: fas
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
        - title: Structural Design Engineer
          company: Turkish Aerospace Industries
          company_url: 'https://www.tusas.com/'
          company_logo: org-TAI
          location: Islamabad, Pakistan
          date_start: '2023-01-02'
          date_end: '2024-05-20'
          description: |2-
              Responsibilities include:
              * Led the design of the vertical stabiliser for 5th gen fighter using CATIA V5
              * Utilised CFRP Composites and aluminium for the manufacturing of aircraft parts
              * Utilised additive manufacturing for the manufacturing of aircraft duct and control surfaces
              * Delivered manufacturing and assembly drawings using CATIA V5 and GD&T
              * Delivered working prototype of the design
    
        - title: Assistant Manager
          company: Facility of Advanced Research and Integrated Systems
          company_url: ''
          company_logo: org-POF
          location: Islamabad, Pakistan
          date_start: '2022-09-05'
          date_end: '2022-12-31'
          description: |2-
              Responsibilities include:
              * Utilized SolidWorks to lead the design of tilt-wing and tilt-rotor eVTOL UAV
              * Delivered assemblies, structure and parts using Solidworks
              * Used CFRP and GFRP Composites for the manufacturing of aircraft parts
              * Delivered manufacturing and assembly drawings using CATIA V5 and GD&T
         
      columns: '2'
        
        - title: R&D Intern
          company: Dawlance Arcelik
          company_url: 'https://www.dawlance.com.pk/'
          company_logo: org-Arcelik
          location: Karachi, Pakistan
          date_start: '2022-07-15'
          date_end: '2022-08-31'
          description: |2-
              Responsibilities include:
              * Delivered model-predictive refrigeration model using MATLAB and Simulink
              * Reduced laboratory costs by $3000/month
              * Validated model results within the HVAC lab
    
         
      columns: '2'
    
        - title: Industrial Project
          company: National Engineering and Scientific Commission
          company_url: 'https://www.nti.org/education-center/facilities/national-engineering-and-scientific-commission-nescom/'
          company_logo: org-NESCOM
          location: Islamabad, Pakistan
          date_start: '2021-04-01'
          date_end: '2022-06-31'
          description: |2-
              Responsibilities include:
              * Utilized SolidWorks to lead the design of fixed-wing eVTOL UAV
              * Delivered mathematical models for the conceptual/preliminary design phase using MATLAB
              * Delivered additively manufactured motor mounts
              * Performed FEA analyses of motor mounts using ANSYS
              * Achieved Rector's Gold Medal for best undergraduate project and thesis
         
      columns: '2'

        - title: R&D Intern
          company: Qadri Group of Companies
          company_url: 'https://www.qadrigroup.pk/'
          company_logo: org-QG
          location: Lahore, Pakistan
          date_start: '2021-07-15'
          date_end: '2022-09-04'
          description: |2-
              Responsibilities include:
              * Researched and investigated assembly Lines for high-speed gears and gear-boxes Manufacturing
              * Proposed new assembly line, upgradation plan and machines for gear manufacturing
              * Analyzed market local industry import data and feasibility of gear manufacturing
         
      columns: '2'
  
  
        
  - block: accomplishments
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
        - certificate_url: 'https://drive.google.com/file/d/1Y7GEiKHXdJl56Kk0JUUsTffC5tkWRxjW/view?usp=sharing'
          date_end: ''
          date_start: '2022-12-25'
          description: 'Acceptance Letters from Imperial College London and University of Toronto under "75 Celebration of Independence Day of Pakistan Scholarship Program"'
          organization: Imperial College London and University of Toronto
          organization_url: https://www.imperial.ac.uk/
          title: 75th Celebration of Independence Day of Pakistan Scholarship Program
        - certificate_url: 'https://drive.google.com/file/d/1F9UDgnnjY3gvX7p7tDqT-ZfB8jA7F5ZZ/view?usp=sharing'
          date_end: ''
          date_start: '2022-06-25'
          description: 'Awarded for Best Undergraduate Thesis and Project'
          organization: National University of Sciences and Technology
          organization_url: https://www.nust.edu.pk
          title: Rector's Gold Medal
        - certificate_url: 'https://drive.google.com/file/d/1nyZhZ5fDcWBgQ_5kUEZd68j9b8b94oLD/view?usp=sharing'
          date_end: ''
          date_start: '2020-12-26'
          description: Awarded for Positions in Student Competitions
          organization: National University of Sciences and Technology
          organization_url: https://www.nust.edu.pk
          title: Certificate and Gold Medal of Merit
        - certificate_url: 'https://drive.google.com/file/d/1y-THC-GZ7H4OvJGu0DFBBvztCJNq9cu0/view?usp=sharing'
          date_end: ''
          date_start: '2022-04-26'
          description: 3rd Position in ASME Speed CAD Challenge
          organization: American Society of Mechanical Engineers
          organization_url: https://www.asme.org
          title: ASME Speed Design Challenge
        - certificate_url: 'https://drive.google.com/file/d/1u3zTptTHnvG3WgAp6xMAT0vkN8NhzqCx/view?usp=sharing'
          date_end: ''
          date_start: '2020-12-26'
          description: 3rd Position in ASME National Team CAD Challenge
          organization: American Society of Mechanical Engineers
          organization_url: https://www.asme.org
          title: ASME Team Design Challenge
       
       #  url: 'https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals'
       #        - certificate_url: https://www.datacamp.com
       #          date_end: '2020-12-21'
       #          date_start: '2020-07-01'
       #          description: ''
       #          organization: DataCamp
       #          organization_url: https://www.datacamp.com
       #          title: 'Object-Oriented Programming in R'
       #          url: ''
    design:
      columns: '2'
#  - block: accomplishments
#    content:
       # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
 #      title: 'Certifications'
 #      subtitle:
 #   items:
 #       - certificate_url: 'https://www.coursera.org/account/accomplishments/verify/MYAF9UCH87WK'
  #        date_end: ''
  #        date_start: '2022-06-25'
  #        description: 'Modern Robotics: Mechanics, Planning, and Control Specialization'
  #        organization: Coursera
  #        organization_url: 'https://www.coursera.org/'
  #        title: "Modern Robotics, Course 1: Foundations of Robot Motion"
  #        url: 'https://www.coursera.org/learn/modernrobotics-course1'
#    design:
 #     columns: '2'
      
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
 #        exclude_future: false
 #        exclude_past: false
 #        publication_type: ""
 #      # Choose how many pages you would like to offset by
 #      offset: 0
 #      # Page order: descending (desc) or ascending (asc) date.
 #      order: desc
 #    design:
 #      # Choose a layout view
 #      view: compact
 #      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 1
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Aerial Robotics
          tag: Aerial Robotics
        - name: Student Competitions
          tag: Student Competitions
        - name: Internship Projects
          tag: Internship Projects
        - name: Control Systems
          tag: Control Systems

    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
 #        - block: markdown
 #          content:
 #            title: Gallery
 #            subtitle: ''
 #            text: |-
 #              {{< gallery album="demo" >}}
 #          design:
 #            columns: '1'
 #        - block: collection
 #          id: featured
 #          content:
 #            title: Featured Publications
 #            filters:
 #              folders:
 #                - publication
 #              featured_only: true
 #          design:
 #            columns: '2'
 #            view: card
  - block: collection
    id: featured
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
 #        - block: collection
 #          id: talks
 #          content:
 #            title: Recent & Upcoming Talks
 #            filters:
 #              folders:
 #                - event
 #          design:
 #            columns: '2'
 #            view: compact
 #        - block: tag_cloud
 #          content:
 #            title: Popular Topics
 #          design:
   #          columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
 #            subtitle:
 #            text: |-
 #              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
 #            # Contact (add or remove contact options as necessary)
      email: aqiphabib.memon@tai.com.tr
      phone: +923322768755
 #            appointment_url: 'https://calendly.com'
      address:
        street: Turkish Aerospace Industries, National Science Technological Park
        city: Islamabad
        region: Captial Territory
 #                      postcode: '94305'
        country: Pakistan
        country_code: PK
 #            directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #           office_hours:
   #            - 'Monday 10:00 to 13:00'
   #            - 'Wednesday 09:00 to 10:00'
 #            contact_links:
 #              - icon: twitter
 #                icon_pack: fab
 #                name: DM Me
 #                link: 'https://twitter.com/Twitter'
 #              - icon: skype
 #                icon_pack: fab
 #                name: Skype Me
 #                link: 'skype:echo123?call'
 #              - icon: video
 #                icon_pack: fas
 #                name: Zoom Me
 #                link: 'https://zoom.com'
 #            # Automatically link email and phone or display as text?
 #            autolink: true
 #            # Email form provider
 #            form:
 #              provider: netlify
 #              formspree:
 #                id:
 #              netlify:
 #                # Enable CAPTCHA challenge to reduce spam?
 #                captcha: false
    design:
      columns: '2'
---
