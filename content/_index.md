---
# Leave the homepage title empty to use the site title
title:
date: 2023-01-29
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      # text: Welcome! I'm a researcher at Princeton SPIA, where I focus on civil-military relations and political violence, with an emphasis on North Africa and the Middle East.
    # variation: '2'
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
        - title: Associate Research Scholar
          company: Princeton University
          company_url: 'https://spia.princeton.edu/'
          company_logo: Princeton
          location: New Jersey
          date_start: '2022-07-01'
          date_end: ''
          # description: |2-
          #     Responsibilities include:

          #     * Analysing
          #     * Modelling
          #     * Deploying
        - title: Lecturer
          company: Yale University
          company_url: 'https://politicalscience.yale.edu/'
          company_logo: Yale
          location: Connecticut
          date_start: '2018-07-01'
          date_end: '2022-06-30'
          # description: Taught electronic engineering and researched semiconductor physics.
    design:
      columns: '2'
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  #   design:
  #     columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
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
      # buttons:
      #   - name: All
      #     tag: '*'
      #   - name: Deep Learning
      #     tag: Deep Learning
      #   - name: Other
      #     tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
  - block: collection
    id: featured
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        featured_only: false
    design:
      columns: '2'
      view: citation
  - block: markdown
    id: writing
    content:
      title: Other Writing
      subtitle: ''
      text: |2-
        [Review of *The Contemporary Middle East in an Age of Upheaval* ed. by James L. Gelvin.](https://muse.jhu.edu/article/865513) *The Middle East Journal 76,* no. 2 (2022): 289-290. {{% staticrefbtn "uploads/writing/gelvin-review.pdf" %}}PDF{{% /staticrefbtn %}}

        [Tunisia’s president launched a political crisis. Is it a coup?](https://www.washingtonpost.com/politics/2021/07/29/tunisias-president-launched-political-crisis-is-it-coup/), *Washington Post*, July 29, 2021. {{% staticrefbtn "uploads/writing/monkeycage2021.pdf" %}}PDF{{% /staticrefbtn %}}

        [Islamism in Civil War](https://apsamena.org/2020/06/01/mena-politics-newsletter-31-spring-2020/), *APSA MENA Politics Newsletter 3*(1), Spring 2020. {{% staticrefbtn "uploads/writing/apsa-mena-politics-newsletter-spring-2020-1.pdf" %}}PDF{{% /staticrefbtn %}}

        [Public Trust in Arab Armies](https://carnegieendowment.org/sada/77610), *Sada*, Carnegie Middle East Center, Oct. 1, 2018. {{% staticrefbtn "uploads/writing/Public-Trust-in-Arab-Armies.pdf" %}}PDF{{% /staticrefbtn %}} {{% staticrefbtn "https://carnegieendowment.org/sada/77611?lang=ar" %}}عربي{{% /staticrefbtn %}}

    design:
      columns: '2'
  - block: markdown
    id: teaching
    content:
      title: Teaching
      subtitle: ''
      text: |2-
        {{% staticref "uploads/courses/GLBL288.pdf" "newtab" %}}Civil-Military Relations (Yale){{% /staticref %}}
        {{% staticref "uploads/courses/PLSC221.pdf" "newtab" %}}American Extremism (Yale){{% /staticref %}}
        {{% staticref "uploads/courses/GLBL603.pdf" "newtab" %}}Political Economy of Terrorism (Yale){{% /staticref %}}
        {{% staticref "uploads/courses/PLSC121.pdf" "newtab" %}}IR of the Middle East (Yale){{% /staticref %}}
        {{% staticref "uploads/courses/PLSC111.pdf" "newtab" %}}Intro to International Relations (Yale){{% /staticref %}}

    design:
      columns: '2'
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      email: nlotito@princeton.edu
      phone: ''
      appointment_url: 'https://calendly.com/nicklotito/'
      # address:
      #   street: Princeton University
      #   city: Princeton
      #   region: NJ
      #   postcode: '08540'
      #   country: United States
      #   country_code: US
      directions: 
        118 Bendheim Hall, Princeton University
      office_hours: 'By appointment only'
        # - 'Monday 10:00 to 13:00'
        # - 'Wednesday 09:00 to 10:00'
      coordinates:
        latitude: '40.348700'
        longitude: '-74.654157'
      contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     # name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Virtual Office (Zoom)
          link: 'https://princeton.zoom.us/my/nlotito'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
