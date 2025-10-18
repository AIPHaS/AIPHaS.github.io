---
# Leave the homepage title empty to use the site title
title:
date: 2025-10-18
type: landing

sections:
  - block: hero
    content:
      title: |
        AIPHaS
        Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        "The AI, Public Health, and Statistical Sciences (AIPHaS) Research Group, established in 2022, brings together expertise in artificial intelligence, statistical sciences, and public health to explore innovative solutions to real-world challenges. Our work focuses on how intelligent systems and statistical approaches can uncover new insights, enhance decision-making, and drive meaningful progress across diverse fields. AIPHaS is committed to advancing research, fostering collaboration, and promoting the responsible use of data and technology to create a smarter and healthier future."
  
  #- block: collection
  #  content:
  #    title: Latest News
   #   subtitle:
   #   text:
   #   count: 5
   #   filters:
   #     author: ''
    #    category: ''
   #     exclude_featured: false
   #     publication_type: ''
   #     tag: ''
   #   offset: 0
   ##   order: desc
   #   page_type: post
   # design:
   #   view: card
   #   columns: '1'
  
 # - block: markdown
  #  content:
   #   title:
    #  subtitle: ''
     # text:
    #design:
     # columns: '1'
      #background:
       # image: 
        #  filename: coders.jpg
         # filters:
          #  brightness: 1
          ##parallax: false
          #position: center
          #size: cover
          #text_color_light: true
      #spacing:
       # padding: ['20px', '0', '20px', '0']
      #css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  #- block: markdown
   ## content:
     # title:
      #subtitle:
      #text: |
       # {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    #design:
     # columns: '1'
---
