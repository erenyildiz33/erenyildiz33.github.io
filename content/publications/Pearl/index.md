---
title: 'PEARL: Power- and Energy-Aware Multicore Intermittent Computing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Khakim Akhunov
- admin
- Kasim Sinan Yildirim

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-07-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "The 22nd International Conference on Embedded Wireless Systems and Networks"
publication_short: "EWSN'25"

abstract: Low-power multicore platforms are suitable for running data- intensive tasks in parallel, but they are highly inefficient for computing on intermittent power. In this work, we present PEARL (PowEr And eneRgy- aware MuLticore Intermittent Computing), a novel systems support that can make existing multicore microcontroller (MCU) platforms suitable for efficient intermittent computing. PEARL achieves this by leveraging only a three-threshold voltage tracking circuit and an external fast non-volatile memory, which multicore MCUs can smoothly interface. PEARL software runtime manages these components and performs energy- and power-aware adaptation of the multicore configuration to introduce minimal backup overheads and boost performance. Our evaluation shows that PEARL outperforms the state-of-the-art solutions by up to 30× and consumes up to 32× less energy.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Intermittent Computing
  - Multicore Microcontrollers
  - Intermittent Runtime

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    # doi: 10.1145/3698384.3699617

# Custom links
links:
  # - type: pdf
  #   url: "https://dl.acm.org/doi/pdf/10.1145/3698384.3699617"
- type: code
  url: https://github.com/tinysystems/PEARL
# - type: slides
#   url: https://www.usenix.org/sites/default/files/conference/protected-files/osdi22_slides_yildiz.pdf
# - type: video
#   url: https://www.youtube.com/watch?v=UCHdCsKG0WQ&t=3s


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
