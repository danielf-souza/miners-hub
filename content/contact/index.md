---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: people
    content:
      title: Organizing Committee
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Organizing Committee
        #  - Principal Investigators
        #  - Researchers
        #  - Grad Students
        #  - Administration
        #  - Visitors
        #  - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
  - block: contact
    content:
      title: Contact
      text: |-
        For further information on next event, write us a message.
      #email: danielfernando.desouza@polimi.it
      #phone: 888 888 88 88
      directions: "Next Event: Catholic University of the Sacred Heart - Department of Economic Policy"
      address:
        street:  Largo Fra Agostino Gemelli, 1
        city: Milan
        region: MI
        postcode: '20123'
        country: Italy
        country_code: IT
      coordinates:
        latitude: '45.461881'
        longitude: '9.177055'
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      #appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
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
      columns: '1'

 # - block: markdown
 #   content:
 #     title:
 #     subtitle: ''
 #     text:
 #   design:
 #     columns: '1'
 #     background:
 #       image: 
 #         filename: seminar_public.jpg
 #         filters:
 #           brightness: 1
 #         parallax: false
 #         position: center
 #         size: cover
 #         text_color_light: true
 #     spacing:
 #       padding: ['20px', '0', '20px', '0']
 #     css_class: fullscreen
---
