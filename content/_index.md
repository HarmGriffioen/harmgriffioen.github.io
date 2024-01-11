---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: skills
  #   content:
  #     title: Skills
  #     text: ''
  #     # Choose a user to display skills from (a folder name within `content/authors/`)
  #     username: admin
  #   design:
  #     columns: '1'
  # - block: experience
  #   content:
  #     title: Experience
  #     # Date format for experience
  #     #   Refer to https://docs.hugoblox.com/customization/#date-format
  #     date_format: Jan 2006
  #     # Experiences.
  #     #   Add/remove as many `experience` items below as you like.
  #     #   Required fields are `title`, `company`, and `date_start`.
  #     #   Leave `date_end` empty if it's your current employer.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - title: CEO
  #         company: GenCoin
  #         company_url: ''
  #         company_logo: org-gc
  #         location: California
  #         date_start: '2021-01-01'
  #         date_end: ''
  #         description: |2-
  #             Responsibilities include:

  #             * Analysing
  #             * Modelling
  #             * Deploying
  #       - title: Professor of Semiconductor Physics
  #         company: University X
  #         company_url: ''
  #         company_logo: org-x
  #         location: California
  #         date_start: '2016-01-01'
  #         date_end: '2020-12-31'
  #         description: Taught electronic engineering and researched semiconductor physics.
  #   design:
  #     columns: '2'
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        For questions or collaboration opportunities, please contact me using the email address below.
      # Contact (add or remove contact options as necessary)
      email: h.j.griffioen@tudelft.nl
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      address:
        street: Van Mourik Broekmanweg 5
        city: Delft
        # region: CA
        postcode: '2628 XE'
        country: Netherlands
        country_code: NL
      directions: Room 02.220
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '51.99957766428124'
        longitude: '4.377686662670541'  
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
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
