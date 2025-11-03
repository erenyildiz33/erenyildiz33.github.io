---
title: "CapDYN: Adaptive Self-Scaling Energy Storage for Powering Batteryless IoT"
authors:
- Maria Doglioni
- Admin
- Matteo Nardello
- Khakim Akhunov
- Kasim Sinan Yildirim
- Davide Brunelli

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2025-09-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "ACM Transactions on Embedded Computing Systems, 2025"
publication_short: "TECS 2025"

abstract: Battery-free devices collect the harvested ambient energy in their energy storage capacitors. The size of the storage capacitor is one of the main factors affecting the device’s active time and power failure rate. In fact, a larger capacitor ensures energy autonomy for longer operations, while a smaller capacitor charges faster and shrinks inefficient cold starts. This paper presents CapDYN , a new energy storage architecture that can self-adapt its capacity based on incoming ambient energy. CapDYN automatically reconfigures the size of its capacitor bank to both speed up charging and improve execution rate. CapDYN reduces the startup time by up to 98% and can schedule tasks up to 38% faster, compared to a fixed-size capacitor. CapDYN operates in a fully autonomous manner consuming down to 11.6 µW in its simplest implementation and replaces the power-hungry microcontroller governing the switching operation with a dedicated ultra-low-power circuit built with COTS components. Its power consumption improves the previous state of the art by 73%, all the while featuring uncompromising reactivity. CapDYN can instantly react to sudden power transients without incurring extra power draw by foregoing MCU-driven reconfiguration used in state-of-the-art dynamic energy storages.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Energy Storage Architecture
- Batteryless Hardware
- Reconfigurable Capacitor Bank
featured: false

hugoblox:
  ids:
    url: https://dl.acm.org/doi/pdf/10.1145/3737288

links:
  - type: pdf
    url: https://dl.acm.org/doi/pdf/10.1145/3737288
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
