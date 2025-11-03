---
title: 'Fast-Inf: Ultra-Fast Embedded Intelligence on the Batteryless Edge'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Leonardo Lucio Custode
- Pietro Farina
- admin
- Renan Beran Kılıç
- Kasim Sinan Yildirim
- Giovanni Iacca

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-07-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "The 22nd ACM Conference on Embedded Networked Sensor Systems"
publication_short: "SenSys'24"

abstract: Batteryless edge devices are extremely resource-constrained compared to traditional mobile platforms. Existing tiny deep neural network (DNN) inference solutions are problematic due to their slow and resource-intensive nature, rendering them unsuitable for batteryless edge devices. To address this problem, we propose a new approach to embedded intelligence, called Fast-Inf, which achieves extremely lightweight computation and minimal latency. Fast-Inf uses binary tree-based neural networks that are ultra-fast and energy-efficient due to their logarithmic time complexity. Additionally, Fast-Inf models can skip the leaf nodes when necessary, further minimizing latency without requiring any modifications to the model or retraining. Moreover, Fast-Inf models have significantly lower backup and runtime memory overhead. Our experiments on an MSP430FR5994 platform showed that Fast-Inf can achieve ultra-fast and energy-efficient inference (up to 700x speedup and reduced energy) compared to a conventional DNN.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Tiny Machine Learning
  - Intermittent Runtime
  - Fast Feed Forward Networks


# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1145/3666025.3699335

# Custom links
links:
  - type: pdf
    url: "https://dl.acm.org/doi/pdf/10.1145/3666025.3699335"
  - type: code
    url: "https://github.com/DIOL-UniTN/Fast-Inf-FFF"


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
projects:
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
<!-- 
> [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
