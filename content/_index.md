---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Material Mechanics Lab
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        Welcome to the Material Mechanics Lab (**MM-Lab**)@[Great Bay University](https://www.gbu.edu.cn/?lang=en), where our research team is focusing on multiphysics coupling, phase-field modeling, machine learning, finite element simulation, and their applications in the field of solid mechanics. Utilizing state-of-the-art computational tools and theories, our goal is to investigate the microscale material behavior that play a critical role in determining large-scale material performance. This exploration is pivotal for driving progress in sustainable materials technologies and beyond.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
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
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---