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
  - block: collection
    id: collection
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
      email: h.j.griffioen@tudelft.nl
      address:
        street: Van Mourik Broekmanweg 5
        city: Delft
        postcode: '2628 XE'
        country: Netherlands
        country_code: NL
      directions: Room 02.220
      coordinates:
        latitude: '51.99957766428124'
        longitude: '4.377686662670541'  
      autolink: true
    design:
      columns: '2'
---
