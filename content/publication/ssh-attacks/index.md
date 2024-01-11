---
title: "Fingerprinting tooling used for SSH compromisation attempts"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Vincent Ghiette
  - admin
  - Christian Doerr

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2019-09-23T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Symposium on Research in Attacks, Intrusions and Defenses*

abstract: "In SSH brute forcing attacks, adversaries try a lot of different user name and password combinations in order to compromise a system. As such activities are easily recognizable in log files, sophisticated adversaries distribute brute forcing attacks over a large number of origins. Effectively finding such distributed campaigns proves however to be a difficult problem.

In practice, when adversaries would spread out brute-forcing over multiple sources, they would likely reuse the same kind of software across all of these origins to simplify their operation and reduce cost. This means if we are able to identify the tooling used in these attempts, we could cluster similar tool usage into likely collaborating hosts and thus campaigns. In this paper, we demonstrate that it is possible to utilize cipher suites and SSH version strings to generate a unique fingerprint for a brute-forcing tool used by the attacker.

Based on a study using a large honeynet with over 4,500 hosts, which received approximately 35 million compromisation attempts over the period of one month, we are able to identify 49 tools from the collected data, which correspond to off-the-shelf tools, as well as custom implementations. The method is also able to fingerprint individual versions of tools, and by revealing mismatches between advertised and actually implemented features detect hosts that spoof identifying information. Based on the generated fingerprints, we are able to correlate login credentials to distinguish distributed campaigns. We uncovered specific adversarial behaviors, tactics and procedures, frequently exhibiting clear timing patterns and tight coordination."

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

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
