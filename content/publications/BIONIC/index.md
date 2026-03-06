---
title: "BIONIC: A Co-Designed Hardware and Runtime for Time-Sensitive Battery-Free IoT"
authors:
- admin
- Davide Cavedon
- Stefano Antonio Putelli
- Josiah Hester
- Kasım Sinan Yıldırım
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

abstract: >
  We introduce BIONIC (duraBle tImekeeper fOr iNtermIttent Computing), a novel
  power system architecture and software runtime that facilitates time-sensitive
  intermittent computing for batteryless Internet of Things. BIONIC integrates
  timekeeping into energy storage hardware: its power system comprises two energy
  storage capacitors. BIONIC switches between these two energy storage capacitors
  to estimate ambient power. Using these estimations, BIONIC can predict and
  track charging times (i.e., off-time durations) to schedule time-sensitive tasks
  and complete them on time. Our evaluations showed that BIONIC significantly
  extends the measurable off-time intervals by a factor of 15 to 1620 compared to
  state-of-the-art, while achieving an accuracy of up to 99.1% and effectively
  adapting to new energy conditions. Besides, in a typical batteryless application,
  BIONIC’s power-aware intermittent computing runtime boosted the number of
  completed time-sensitive operations by 30% while reducing failed timely
  operations by 29%.
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
