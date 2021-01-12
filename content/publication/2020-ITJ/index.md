---
title: "ME-TLS: Middlebox-Enhanced TLS for Internet-of-things Devices"
authors:
- Jie Li
- admin
- Jinshu Su
- Xinyi Huang
- Xiaofeng Wang

date: "2019-11-15T00:00:00Z"
doi: "10.1109/JIOT.2019.2953715"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Internet of Things Journal*"
publication_short: "*ITJ*"

abstract: "In-network middleboxes are vital for Internet-of-things system security, but the widely adopted Transport Layer Security
(TLS) protocol blinds application-level middleboxes due to the encryption of traffic data. To resolve this problem, many solutions have
been proposed to date. Among them, SplitTLS is widely adopted in the industry by proxy manufacturers. It requires TLS client to install
customized root certificates and incurs additional security flaws, e.g., disabling server authentication and using weak cipher suites.
Another approach is to customize the TLS protocol where middleboxes are enabled via either performing handshake directly with TLS
endpoints, or receiving session key materials in an out-of-band manner. Overall, current solutions would either jeopardize the original
TLS handshake procedure, or incur additional overheads on the endpoints.
<br/>In this paper we design a new middlebox-enhanced TLS (ME-TLS), which enables endpoints to introduce authenticated middleboxes
into a TLS session while control middleboxes’ access permission and processing order of traffic data. Particularly, in our proposed
ME-TLS, the handshake structure of TLS keeps unchanged and middleboxes work in a passive manner. That is, middleboxes in the
ME-TLS could recover session key materials by monitoring handshake messages passively instead of interacting with endpoints,
secondary secure channels for key transmission are also not needed in our ME-TLS. We implement our ME-TLS based on TLS 1.3
protocol and evaluate its performances. The experiment results demonstrate that our proposal is practical and deployable for real-world
IoT scenarios."

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
  caption: 'Fig.1 **System architecture**'
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


