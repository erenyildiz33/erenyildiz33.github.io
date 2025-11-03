---
title: 'Bootstrapping Health Wearables Powered by Intra-Body Power Transfer'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Saad Ahmed
- admin
- Shashank Holla
- Noor Mohammed
- Bashima Islam
- Kasim Sinan Yildirim
- Jeremy Gummeson
- Sunghoon Ivan Lee
- Josiah Hester

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
publication: "IEEE 20th International Conference on Body Sensor Networks"
publication_short: "BSN'24"

abstract: Continuous health monitoring is crucial to ensuring better health and taking preventive measures just-in-time. Existing battery-powered health wearables pose a significant limitation to continuous monitoring as batteries wear out after fixed energy cycles and need replacement. Ambient energy harvesting unlocks battery-free sensing but it suffers from spatio-temporal variability, making it unfit for health sensing. Intra-body power transfer (IBPT) provides an alternative energy source for battery-free operation, however, it can only provide limited energy in order to ensure wearer's safety. Existing system support is designed to maximize computational progress in a single energy cycle, thus wasting energy on computations that become stale in the next energy cycle. We instantiate an IBPT-powered health wearable capable of supporting multiple health sensors. To cope with lower incoming energy, we introduce BodyOS; a system support that exposes programming constructs for domain experts to express health applications in terms of the inherent dependencies of bio-signals being monitored by the application. By avoiding unnecessary sensing operations, BodyOS allows energy-efficient application execution and faster capacitor recharge while ensuring that the data sensed by the application is always useful. We evaluate BodyOS to show that it significantly improves energy efficiency, thus increasing the on-time and number of data points collected by the device.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Intermittent Runtime
  - Energy Harvesting
  - Batteryless Hardware

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1109/BSN63547.2024.10780616

# Custom links
links:
  - type: pdf
    url: "https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10780616"


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
