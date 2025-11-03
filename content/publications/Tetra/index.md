---
title: 'Enabling efficient intermittent computing on brand new microcontrollers via tracking programmable voltage thresholds'

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

date: '2023-07-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "The 11th International Workshop on Energy Harvesting & Energy-Neutral Sensing Systems"
publication_short: "ENSsys'23"

abstract: Modern off-the-shelf low-power microcontrollers (MCUs) are optimized to meet the computational requirements of data- and compute-intensive embedded artificial intelligence applications. However, they are not intended for batteryless operation; therefore, they lack fast and low-power non-volatile memory in their architecture. This memory is essential for backup and recovery operations during intermittent execution due to frequent power failures. Connecting an external non-volatile memory to these MCUs exposes a significant time and energy overhead, making them inefficient and even useless for batteryless applications. In this paper, we answer how to enable the adaptation of the brand-new off-the-shelf low-power AI MCUs to the intermittent computing paradigm. To this end, we present a new configurable low-power circuit that brings energy awareness, which is exploited by a novel backup policy that reduces the number of backups significantly. Our evaluation shows that the proposed backup technique reduces the execution latency by 40%, eliminating unnecessary backups and hence decreasing the intermittent computing systems' throughput significantly.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Intermittent Computing
  - Batteryless Hardware
  - Energy Storage Architecture

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1145/3628353.3628547

# Custom links
links:
  - type: pdf
    url: "https://dl.acm.org/doi/pdf/10.1145/3628353.3628547"
# - type: code
#   url: https://github.com/tinysystems/PEARL
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
