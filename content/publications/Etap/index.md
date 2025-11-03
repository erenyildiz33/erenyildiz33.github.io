---
title: "CapDYN: Adaptive Self-Scaling Energy Storage for Powering Batteryless IoT"
authors:
- Ferhat Erata,
- Admin
- Arda Goknil
- Kasim Sinan Yildirim
- Jakub Szefer
- Ruzica Piskac
- Gokcin Sezgin

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-09-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "ACM Transactions on Embedded Computing Systems, 2023"
publication_short: "TECS 2023"

abstract: Energy harvesting battery-free embedded devices rely only on ambient energy harvesting that enables stand-alone and sustainable IoT applications. These devices execute programs when the harvested ambient energy in their energy reservoir is sufficient to operate and stop execution abruptly (and start charging) otherwise. These intermittent programs have varying timing behavior under different energy conditions, hardware configurations, and program structures. This article presents Energy-aware Timing Analysis of intermittent Programs (ETAP), a probabilistic symbolic execution approach that analyzes the timing and energy behavior of intermittent programs at compile time. ETAP symbolically executes the given program while taking time and energy cost models for ambient energy and dynamic energy consumption into account. We evaluate ETAP by comparing the compile-time analysis results of our benchmark codes and real-world application with the results of their executions on real hardware. Our evaluation shows that ETAP’s prediction error rate is between 0.0076% and 10.8%, and it speeds up the timing analysis by at least two orders of magnitude compared to manual testing
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Timing Analysis
- Intermittent Computing
- Batteryless Sensors
- Energy Harvesting
featured: false

hugoblox:
  ids:
    doi: 10.1145/3563216

links:
  - type: pdf
    url: https://dl.acm.org/doi/pdf/10.1145/3563216
  # - type: code
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: dataset
  #   url: ""
  # - type: poster
  #   url: ""
  # - type: project
  #   url: ""
  # - type: slides
  #   url: https://www.slideshare.net/
  # - type: source
  #   url: ""
  # - type: video
  #   url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
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
<!-- 
> [!NOTE]
> Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the *Slides* button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
