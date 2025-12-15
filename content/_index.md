---
title: '谢姥姥'
date: 2023-10-24
type: landing
sections:
  - block: resume-biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      spacing:
        padding: [0, 0, 0, 0]
      biography:
        style: 'text-align: justify;'
      # Avatar customization
      avatar:
        size: large
        shape: circle
  - block: collection
    content:
      filters:
        folders:
          - blog
    design:
      view: compact  # 【新增】必须指定视图样式，否则会报错！
      spacing:
        padding: ['3rem', 0, '6rem', 0]
---
