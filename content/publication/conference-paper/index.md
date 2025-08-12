---
title: 'Automatic Unit Test Generation for Programming Assignments Using Large Language Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yuanyang Shen
  - Yida Tao

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-04-16T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-08-13T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Software Engineering Education and Training*
publication_short: In *CSEE&T*

abstract: "Programming knowledge is a crucial aspect of computer science education, and unit testing is commonly employed to automatically assess programming assignments. Instructors and teaching assistants typically invest considerable efforts in writing unit tests, which may still be vulnerable to human oversight and mistakes. In this work, we explored the feasibility of using Large Language Models (LLMs) to automate the assessment of programming assignments. In particular, we proposed two approaches: the plain approach that uses GPT-4o-mini in a vanilla setting, and the augmented approach that integrates additional strategies such as tailored prompts with syntax and semantic constraints, and a feedback mechanism with information on test-effectiveness metrics. We evaluate the two approaches on six real-world programming assignments from an introductory-level programming course at our university. Compared to the plain approach, the augmented approach improves the usability and effectiveness of the generated unit tests, reducing 85 % compilation errors while enhancing the statement coverage and mutation scores by 1.7 x and 2.1 x, respectively. In addition, the augmented approach also complements human-written tests by covering additional program behaviors. In a case study of 1296 students' submissions that pass human-written tests, the augmented approach successfully detected new bugs in 13 % submissions, with an accuracy of 27 %. These results not only demonstrate the potentials of LLMs in generating useful unit tests for programming assignments, but also highlight the strategies that can effectively enhance LLMs' capabilities to augment human-written tests, offering practical benefits for both educators and students."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Large Language Models
  - Programming Assignment
  - Unit Test Generation

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
