---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        Send message to me.
      email: yangbai90@outlook.com
      phone: 888 888 88 88
      address:
        street: Building A5,Songshanhu International Community
        city: Dongguan
        region: Guangdong
        postcode: '523000'
        country: China
        country_code: CN
      coordinates:
        latitude: 'null'
        longitude: 'null'
      directions: null
      office_hours:
        - 'Monday 09:00 to 17:00'
        - 'Tuesday 09:00 to 17:00'
        - 'Wednesday 09:00 to 10:00'
        - 'Thursday 09:00 to 17:00'
        - 'Friday 09:00 to 17:00'
      # appointment_url: 'https://calendly.com'
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

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
