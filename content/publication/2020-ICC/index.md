---
title: "Hybrid Routing: Towards Resilient Routing in Anonymous Communication Networks"
authors:
- Yusheng Xia
- admin
- Jinshu Su
- Chen Pan

date: "2020-06-07T00:00:00Z"
doi: "10.1109/ICC40277.2020.9149166"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*2020 IEEE International Conference on Communications*"
publication_short: "*ICC 2020*"

abstract: "<p>Anonymous communication networks (ACNs) are intended to protect the metadata during communication. As classic ACNs, onion mix-nets are famous for strong anonymity, in which the source defines a static path and wraps the message multi-times with the public keys of nodes on the path, through which the message is relayed to the destination. However, onion mix-nets lacks in resilience when the static on-path mixes fail. Mix failure easily results in message loss, communication failure, and even specific attacks. Therefore, it is desirable to achieve resilient routing in onion mix-nets, providing persistent routing capability even though node failure. The state-of-theart solutions mainly adopt mix groups and thus need to share secret keys among all the group members which may cause single point of failure. To address this problem, in this work we propose a hybrid routing approach, which embeds the onion mix-net with hop-by-hop routing to increase routing resilience. Furthermore, we propose the threshold hybrid routing to achieve better key management and avoid single point of failure. As for experimental evaluations, we conduct quantitative analysis of the resilience and realize a local T-hybrid routing prototype to test performance. The experimental results show that our proposed routing strategy increases routing resilience effectively, at the expense of acceptable latency.</p>"

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
  caption: 'Fig.1 **The network model**'
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


