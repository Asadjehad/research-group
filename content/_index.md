---
title: 
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        MARNEA Research Group
      text: |
        The **Advanced Materials Research Network for Energy Applications** is a collaborative group focused on the development of advanced materials, including their synthesis, characterization, and theoretical modeling for energy uses.

        This network aims to foster cooperation and dynamic exchange among researchers to improve problem-solving and create new technological innovations.
      background:
        image:
          filename: welcome.jpg
        text_color_light: true
    design:
      fullscreen: true
      overlay: true

  - block: collection
    content:
      title: Latest News
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
      title: Join Our Research Network
      text: |
        We welcome collaborators and researchers working in energy materials, nanotechnology, catalysis, and sustainability. Together, we build solutions for a cleaner and more efficient future.
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 0.6
          parallax: true
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['60px', '0', '60px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title: Our Team
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
