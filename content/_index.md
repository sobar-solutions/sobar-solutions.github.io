---
# Leave the homepage title empty to use the site title
title: Sobar Solutions
date: 2023-11-11
type: landing

sections:
  - block: hero
    content:
      title: |
        Sober Solutions in Data Engineering and AI
      image:
        filename: welcome.png
        size: cover
      text: |
        <br>
        
        London-based Sobar Solutions is a community of scientists and AI engineers. We organised while working together as AI researchers at a major banking institution. We consult businesses, NGOs and science groups, offering efficient and scalable Data Science and AI solutions. 
  
  - block: collection
    content:
      title: Our Offer
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
      page_type: offer
    design:
      view: showcase
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