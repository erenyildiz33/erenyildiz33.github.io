---
title: "Efficient and safe i/o operations for intermittent systems"
authors:
- admin
- Saad Ahmed
- Bashima Islam
- Josiah Hester
- Kasim Sinan Yildirim
date: "2023-04-07T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conferencer"]

# Publication name and optional abbreviated publication name.
publication: " The Eighteenth European Conference on Computer Systems"
publication_short: "EuroSys'23:"

abstract: Task-based intermittent software systems always re-execute peripheral input/output (I/O) operations upon power failures since tasks have all-or-nothing semantics. Re-executed I/O wastes significant time and energy and risks memory inconsistency. This paper presents EaseIO, a new task-based intermittent system that remedies these problems. EaseIO programming interface introduces re-execution semantics for I/O operations to facilitate safe and efficient I/O management for intermittent applications. EaseIO compiler front-end considers the programmer-annotated I/O re-execution semantics to preserve the task's energy efficiency and idem-potency. EaseIO runtime introduces regional privatization to eliminate memory inconsistency caused by idempotence bugs. Our evaluation shows that EaseIO reduces the wasted useful I/O work by up to 3× and total execution time by up to 44% by avoiding 76% of the redundant I/O operations, as compared to the state-of-the-art approaches for intermittent computing. Moreover, for the first time, EaseIO ensures memory consistency during DMA-based I/O operations.
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Intermittent Runtime
- Task-based
- Peripherals

featured: true

hugoblox:
  ids:
    doi: 10.1145/3552326.3587435

links:
- type: pdf
  url: https://dl.acm.org/doi/abs/10.1145/3552326.3587435
- type: code
  url: https://github.com/tinysystems/easeIO
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
