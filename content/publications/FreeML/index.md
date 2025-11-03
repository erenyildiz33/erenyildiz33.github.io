---
title: "Memory-efficient Energy-adaptive Inference of Pre-Trained Models on Batteryless Embedded Systems"
authors:
- Pietro Farina
- Subrata Biswas
- admin
- Khakim Akhunov
- Saad Ahmed
- Bashima Islam
- Kasim Sinan Yildirim
date: "2024-04-07T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conferencer"]

# Publication name and optional abbreviated publication name.
publication: "The 21st International Conference on Embedded Wireless Systems and Networks"
publication_short: "EWSN'24"

abstract: Batteryless systems frequently face power failures, requiring extra runtime buffers to maintain inference progress and leaving only a memory space for storing ultra-tiny deep neural networks (DNNs). Besides, making these models responsive to stochastic energy harvesting dynamics during inference requires a balance between inference accuracy, latency, and energy overhead. Recent works on compression mostly focus on time and memory, but often ignore energy dynamics or significantly reduce the accuracy of pre-trained DNNs. Existing energy-adaptive inference works modify the architecture of pre-trained models and have significant memory overhead. Thus, energy-adaptive and accurate inference of pre-trained DNNs on batteryless devices with extreme memory constraints is more challenging than traditional microcontrollers. We combat these issues by proposing FreeML, a framework to optimize pre-trained DNN models for memory-efficient and energy-adaptive inference on batteryless systems. FreeML comprises (1) a novel compression technique to reduce the model footprint and runtime memory requirements simultaneously, making them executable on extremely memory-constrained batteryless platforms; and (2) the first early exit mechanism that uses a single exit branch for all exit points to terminate inference at any time, making models energy-adaptive with minimal memory overhead. Our experiments showed that FreeML reduces the model sizes by up to , supports adaptive inference with a  less memory overhead, and provides significant time and energy benefits with only a negligible accuracy drop compared to the state-of-the-art.
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Intermittent Runtime
- Task-based
- Tiny Machine Learning
- Early-exit

featured: true

hugoblox:
  ids:
    url: https://arxiv.org/pdf/2405.10426?df

links:
- type: pdf
  url: https://arxiv.org/pdf/2405.10426?
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
