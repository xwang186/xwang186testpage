---
title: Home
sections:
- type: heroblock
  template: heroblock
  section_id: hero
  component: hero_block.html
  content: This section can contain a subtitle or tagline. The recommended length
    is one to three sentences, but can be changed as you prefer.
  title: ''
  actions: []
- type: contentblock
  template: contentblock
  title: About
  section_id: about
  actions:
  - label: Contact Me
    url: "/contact"
  component: content_block.html
  content: This is Xiaohan Wang's blog. I am a software engineer living in Great Seattle
    area right now. I will share some technical notes here about my daily thinking
    & learning. Feel free to reach me for any questions/help.
  image: ''
- type: postsblock
  template: postsblock
  title: Recent Posts
  section_id: recent-posts
  actions:
  - label: View Blog
    url: blog/index.html
  component: posts_block.html
  num_posts_displayed: 4
layout: home
menu:
  main:
    weight: 1

---
