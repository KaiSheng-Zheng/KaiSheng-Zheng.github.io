---
title: 'Automatic Unit Test Generation for Programming Assignments Using Large Language Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yuanyang Shen
  - Yida Tao

date: '2025-04-16T00:00:00Z'
publishDate: '2025-08-13T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

publication:
  name: "2025 IEEE/ACM 37th International Conference on Software Engineering Education and Training (CSEE&T)"
  short_name: "CSEE&T"

peer_reviewed: true

abstract: "Programming knowledge is a crucial aspect of computer science education, and unit testing is commonly employed to automatically assess programming assignments. Instructors and teaching assistants typically invest considerable efforts in writing unit tests, which may still be vulnerable to human oversight and mistakes. In this work, we explored the feasibility of using Large Language Models (LLMs) to automate the assessment of programming assignments. In particular, we proposed two approaches: the plain approach that uses GPT-4o-mini in a vanilla setting, and the augmented approach that integrates additional strategies such as tailored prompts with syntax and semantic constraints, and a feedback mechanism with information on test-effectiveness metrics. We evaluate the two approaches on six real-world programming assignments from an introductory-level programming course at our university. Compared to the plain approach, the augmented approach improves the usability and effectiveness of the generated unit tests, reducing 85 % compilation errors while enhancing the statement coverage and mutation scores by 1.7 x and 2.1 x, respectively. In addition, the augmented approach also complements human-written tests by covering additional program behaviors. In a case study of 1296 students' submissions that pass human-written tests, the augmented approach successfully detected new bugs in 13 % submissions, with an accuracy of 27 %. These results not only demonstrate the potentials of LLMs in generating useful unit tests for programming assignments, but also highlight the strategies that can effectively enhance LLMs' capabilities to augment human-written tests, offering practical benefits for both educators and students."

tags:
  - Large Language Models
  - Programming Assignment
  - Unit Test Generation

featured: true

hugoblox:
  ids:
    doi: 10.1109/CSEET66350.2025.00031

links:
  - type: code
    url: https://github.com/KaiSheng-Zheng/AugGPT

image:
  caption: 'Image credit: **Doubao**'
  focal_point: ''
  preview_only: false

projects: []
slides: ""
aliases:
  - /publication/conference-paper/
---
