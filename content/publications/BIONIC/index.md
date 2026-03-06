---
title: "A Greener Edge: A Framework on Carbon-aware Edge ML System Design"
authors:
- Xuesi Chen
- Ilan Mandel
- admin
- Josiah Hester
- Udit Gupta
date: "2026-04-07T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conferencer"]

# Publication name and optional abbreviated publication name.
publication: "1The 24th ACM International Conference on Mobile Systems, Applications, and Services"
publication_short: "MobiSys 26"

abstract: Edge devices are often deployed at scale, yet their environ- mental impact, shaped by complex interactions between hardware choices, workload demands, power systems, and deployment context, has been overlooked by the mobile com- puting community. We present MicroGreen, a design-time framework that models lifetime carbon emissions for edge ML systems. By combining component-level carbon mod- els with workload profiling and environment-aware energy analysis, MicroGreen identifies carbon-optimal configura- tions across diverse conditions. Our results show that the most energy-efficient processor is not always the most sus- tainable, and that ambient energy availability, inference rate, and deployment lifetime can shift the carbon-optimal design by over an order of magnitude. Through a real vision-based visitor detection and counting deployment in New York City parks, we demonstrate that heterogeneous, location-aware designs reduce total emissions by 47.26% compared to a ho- mogeneous baseline.
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- MobiSys
- Sustainability
- Carbon Footprint

featured: true

hugoblox:
  ids:
    url: https://www.sigmobile.org/mobisys/2026/

links:
- type: pdf
  url: https://www.sigmobile.org/mobisys/2026/
# - type: code
#   url: https://github.com/tinysystems/ImmortalThreads
# - type: slides
#   url: https://www.usenix.org/sites/default/files/conference/protected-files/osdi22_slides_yildiz.pdf
# - type: video
#   url: https://www.youtube.com/watch?v=UCHdCsKG0WQ&t=3s


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- This work is driven by the results in my [previous paper](/publications/conference-paper/) on LLMs.

> [!NOTE]
> Create your slides in Markdown - click the *Slides* button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
