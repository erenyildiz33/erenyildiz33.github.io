---
title: 'On the Accuracy of Network Synchronization Using Persistent Hourglass Clocks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Kasim Sinan Yildirim
- Przemysław Pawełczak
- Josiah Hester

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2019-07-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2019-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "7th International Workshop on Energy Harvesting and Energy-Neutral Sensing Systems"
publication_short: "ENSsys'19"

abstract: Batteryless sensor nodes compute, sense, and communicate using only energy harvested from the ambient. These devices promise long maintenance free operation in hard to deploy scenarios, making them an attractive alternative to battery-powered wireless sensor networks. However, complications from frequent power failures due to unpredictable ambient energy stand in the way of robust network operation. Unlike continuously-powered systems, intermittently-powered batteryless nodes lose their time upon each reboot, along with all volatile memory, making synchronization and coordination difficult. In this paper, we consider the case where each batteryless sensor is equipped with a hourglass capacitor to estimate the elapsed time between power failures. Contrary to prior work that focused on providing a continuous notion of time for a single batteryless sensor, we consider a network of batteryless sensors and explore how to provide a network-wide, continuous, and synchronous notion of time. First, we build a mathematical model that represents the estimated time between power failures by using hourglass capacitors. This allowed us to simulate the local (and continuous) time of a single batteryless node. Second, we show--through simulations--the effect of hourglass capacitors and in turn the performance degradation of the state of the art synchronization protocol in wireless sensor networks in a network of batteryless devices.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Timekeeping
  - Energy Harvesting
  - Batteryless Sensors

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1145/3362053.3363497

# Custom links
links:
  - type: pdf
    url: "https://dl.acm.org/doi/pdf/10.1145/3362053.3363497"


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
