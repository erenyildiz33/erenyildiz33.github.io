---
title: 'On Tracking Time with Better Resolution and Range in Batteryless Systems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Davide Cavedon
- Kasim Sinan Yildirim

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
publication: "12th International Workshop on Energy Harvesting and Energy-Neutral Sensing Systems"
publication_short: "ENSsys'24"

abstract: Accurate and failure-resilient timekeeping is crucial for time-sensitive sensing operations and task scheduling in batteryless systems. The main challenge lies in measuring the duration of power failures precisely. Remanence timekeepers offer a simple and energy-efficient solution by exploiting the discharging characteristics of capacitors to measure the power failure duration. However, existing remanence timekeeping designs in the literature can measure either a shorter power failure duration with a higher resolution or a longer power failure duration with a lower resolution. In this paper, we focus on this trade-off and study how to design an ideal timekeeper offering high measurement resolution and range for batteryless systems. We consider CHRT (cascaded hierarchical remanence timekeeper), the de facto remanence timekeeper for batteryless systems, and improve its design to increase its measurement resolution during longer power failure durations. We evaluate the benefits and trade-offs of our new design. Finally, based on our evaluations, we outline potential improvements and research directions for timekeeping in batteryless systems.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Timekeeping
  - Energy Harvesting
  - Batteryless Hardware

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1145/3698384.3699617

# Custom links
links:
  - type: pdf
    url: "https://dl.acm.org/doi/pdf/10.1145/3698384.3699617"


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
  - example

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
