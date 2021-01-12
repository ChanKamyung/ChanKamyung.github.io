---
title: "Practical Privacy-Preserving Deep Packet Inspection Outsourcing"
authors:
- Jie Li
- Jinshu Su
- admin
- Xiaofeng Wang
- Shuhui Chen

date: "2018-02-07T00:00:00Z"
doi: "10.1002/cpe.4435"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Concurrency and Computation: Practice and Experience*"
publication_short: "*CCPE*"

abstract: "Hardware-based middleboxes are ubiquitous in computer networks, which usually incur high
deployment and management expenses. A recently arising trend aims to address those problems
by outsourcing the functions of traditional hardware-based middleboxes to high volume
servers in a cloud. This technology is promising but still faces a few challenges from different
aspects, including privacy concerns, middlebox functionality, and performance. In this paper,
we propose two practical approaches to implementing a cloud-based DPI middlebox. The outsourced
DPI middlebox performs payload inspection over encrypted traffic while preserving the
privacy of both communication data and inspection rules. Our first approach employs amodified
reversible sketch structure,which is used for efficient error-free membership testing, and our second
approach extends the famous AC pattern matching algorithm to the cipher text domain.We
utilize unkeyed one-way hash functions instead of complex cryptographic protocols to achieve the
privacy preservation requirements. Our system supports a wide range of real-world inspection
rules.We conduct evaluations on the ClamAV rule set, and the experiment results demonstrate
the effectiveness of our proposals."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Cryptographic Protocols for Privacy-Oriented Applications 
featured: false

# links:
# - name: ""
#   url: ""
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Fig.2 **System architecture**'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---


