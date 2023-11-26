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
        filename: welcome.jpg
      text: |
        <br>
        
        London-based Sobar Solutions consists of scientists and AI engineers. We consult businesses, NGOs and science groups, offering efficient and scalable Data Science and AI solutions. Lightweight and efficient machine learning can benefit nearly any enterprise. Our promise is providing the most elegant and efficient solutions irrespective of what is currently in the spotlight. Our mindset is building original systems: lightweight and specific to your needs. We consult, build prototypes and can take projects to production with our in-house talent.

# We are: [Dr Artur Sokolovsky](https://www.linkedin.com/in/sokolokki/) & [Dr Philipp Bartel](https://www.linkedin.com/in/philipp-bartel-86531660/).
  
  - block: collection
    content:
      title: Our Projects
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