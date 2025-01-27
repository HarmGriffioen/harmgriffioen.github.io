---
title: "Have you SYN me? characterizing ten years of Internet scanning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Giorgos Koursiounis
  - Georgios Smaragdakis
  - Christian Doerr

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-11-04T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ACM Internet Measurement Conference*

abstract: "Port scanning is the de-facto method to enumerate active hosts and potentially exploitable services on the Internet. Over the last years, several studies have quantified the ecosystem of port scanning. Each work has found drastic changes in the threat landscape compared to the previous one, and since the advent of high-performance scanning tools and botnets a lot has changed in this highly volatile ecosystem.

Based on a unique dataset of Internet-wide scanning traffic collected in a large network telescope, we provide an assessment of Internet-wide TCP scanning with measurement periods in the last 10 years (2015 to 2024). We collect over 750 million scanning campaigns sending more than 45 billion packets and report on the evolution and developments of actors, their tooling, and targets. We find that Internet scanning has increased 30-fold over the last ten years, but the number and speed of scans have not developed at the same pace. We report that the ecosystem is extremely volatile, where targeted ports and geographical scanner locations drastically change at the level of weeks or months. We thus find that for an accurate understanding of the ecosystem we need longitudinal assessments. We show that port scanning becomes heavily commoditized, and many scanners target multiple ports. By 2024, well-known scanning institutions are targeting the entire IPv4 space and the entire port range."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

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