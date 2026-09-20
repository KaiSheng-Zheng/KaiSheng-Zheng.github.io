---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/` or `data/authors/`)
      username: admin
      text: ""
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I am an undergraduate in Southern University of Science and Technology (SUSTech) studying computer science and technology.

        I personally have some interest in several fields, such as distributed machine learning, model compression and facial tracking in VR.

        Refer to my
        <a href="https://kaisheng-zheng.github.io/experience">personal resume</a>
        or download the
        <a href="https://kaisheng-zheng.github.io/uploads/resume.pdf">English CV</a>
        /
        <a href="https://kaisheng-zheng.github.io/uploads/resume-zh.pdf">中文简历</a>.
    design:
      columns: '1'
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publications
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: '1'
---
