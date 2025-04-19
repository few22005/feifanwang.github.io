---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-04-17
# type: landing


design:
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      background:
        color: white
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I am a Ph.D. student in Economics at the University of Connecticut. My research focuses on financial econometrics, time series forecasting, and bootstrap methods. I develop robust inference tools for high-dimensional predictive models with applications in bond markets and factor-augmented regressions.
        
        Please check out my latest papers and feel free to connect!
    design:
      columns: '1'
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      page_type: post
      count: 3
      order: desc
    design:
      view: date-title-summary
      spacing:
        padding: [1, 1, 1, 1]
---


