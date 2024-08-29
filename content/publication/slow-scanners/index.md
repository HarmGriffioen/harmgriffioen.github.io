---
title: "Quantifying TCP SYN DDoS Resilience: A Longitudinal Study of Internet Services"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Christian Doerr

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2020-04-20T00:00:00Z'
doi: '10.1109/NOMS47738.2020.9110444}'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE/IFIP Network Operations and Management Symposium*

abstract: "To compromise a computer, it is first necessary to discover which hosts are active and which services they run. This reconnaissance is typically accomplished through port scanning. Defense systems monitor for these unsolicited packets and raise an alarm if a predefined threshold is exceeded. To remain undetected, adversaries can either slow down the scan, and/or distribute it over multiple hosts. With each source below the threshold, the combination of all may still complete the scan efficiently. It is especially this group that is of concern: with enough resources and knowledge to execute such a coordinated activity, they will pose a more potent threat than the noisy script kiddie. Correlating which out of 4 billion IPs potentially collaborate is however a challenging task, hence today’s systems do not consider coordination beyond basic subnet aggregation.In this paper, we propose a method to identify and fingerprint distributed scanners based on commonalities in header fields, which are an artifact of the way fast port scanning software is built. We demonstrate that this method can effectively locate groups, and based on the monitoring logs we report on a number of new groups and tools, which have previously not been reported in the academic literature.Fingerprints generated can ultimately be used as Indicators of Compromise to detect and mitigate scanning behavior in order to deny adversaries the possibility to learn about weaknesses of a system."

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