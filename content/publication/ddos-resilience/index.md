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

date: '2020-06-22T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IFIP Networking Conference*

abstract: "One of the most prevalent attacks in the Internet are TCP SYN floods, during which a massive number of malicious connection requests is being sent to a victim that will eventually use up all of the server's resources. In order to make these attacks more difficult to track back and defend against, SYN floods are typically injected with spoofed source addresses, which provides the interesting side effect that an “echo” of ongoing attacks becomes visible through the resulting background noise. This paper provides a longitudinal study of this Internet backscatter received at more than 65,000 IP addresses over a period of 5 years, which allows us to quantify the types of victims that are attacked, the attack duration and intensity, and whether services collapse under the load - thereby providing an insight into the resilience of services provided publicly on the Internet. Our findings show that DDoS attacks have significantly changed in type and magnitude within this relatively short period of time, however we also see that Internet services by-and-large co-evolved with the increased threat landscape and become increasingly better provisioned, yet at a rate insufficient to keep up with the growth of attacks."

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