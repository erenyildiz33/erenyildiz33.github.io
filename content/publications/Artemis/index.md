---
title: 'Adaptable Runtime Monitoring for Intermittent Systems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Khakim Akhunov
- Lorenzo Antonio Riva
- Arda Goknil
- Ivan Kurtev
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
publication: "The 19th European Conference on Computer Systems "
publication_short: "EuroSys'24"

abstract: Batteryless energy harvesting devices compute intermittently due to power failures that frequently interrupt the computational activity and lead to charging delays. To ensure functional correctness in intermittent computing, applications must exhibit several unique properties, such as guarantees for computational progress despite power failures and prevention of stale operations caused by charging delays. We observe that current software support for intermittent computing allows for checking only a fixed set of properties and leads to tightly coupled application and property-checking, thus hampering modularity, scalability, and maintainability. In this paper, we present ARTEMIS, the first framework designed to facilitate flexible property checking of intermittent programs at runtime. ARTEMIS is developed based on techniques from the area of runtime monitoring, offers a specification language for specifying an open set of properties, and provides automatic generation of monitors responsible for checking the properties. Our evaluation showed that ARTEMIS achieves comparable efficiency to state-of-the-art solutions while significantly preventing failure scenarios through its monitoring capabilities.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Intermittent Runtime
  - Intermittent Computing
  - Runtime Monitoring


# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1145/3627703.3650070

# Custom links
links:
  - type: pdf
    url: "https://dl.acm.org/doi/pdf/10.1145/3627703.3650070"
  - type: code
    url: "hhttps://github.com/tinysystems/ARTEMIS"


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
