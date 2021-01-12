---
title: "Hybrid Routing: Balancing Anonymity and Resilience in Anonymous Communication Networks"
authors:
- Yusheng Xia
- admin
- Jinshu Su
- Hongcheng Zou

date: "2020-11-12T00:00:00Z"
doi: "10.1016/j.cose.2020.102106"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Computers & Security*"
publication_short: "*CS*"

abstract: "<p>Anonymous communication networks (ACNs) are intended to protect the metadata privacy during the communication. As typical ACNs, onion mix-nets adopt source routing where the source defines a static path and wraps the message with the public keys of on-path nodes so that the message could be delivered to the destination. However, onion mix-nets lack resilience when the static on-path mixes fail, which could result in message loss, communication failure and even de-anonymization attacks. Therefore, it is desirable to achieve routing resilience in onion mix-nets for persistent routing capability even against node failure. The state-of-the-art solutions mainly adopt mix groups and thus need to share secrets among all the group members, which may cause single point of failure and render massive loss of anonymity.</p>
<p>To address the above problem, in this work we design a hybrid routing approach, which essentially embeds the onion mix-net with hop-by-hop routing to achieve desirable routing resilience. Furthermore, we extend our scheme with a threshold setting, and propose T-hybrid routing to mitigate the anonymity loss when group mixes are compromised. Besides, we propose the active defense mechanism to defend replay attacks in the scenario of mix groups. As for experimental evaluations, we conduct a quantitative analysis of the resilience and anonymity for various schemes, and demonstrate that T-hybrid routing can achieve a good balance between resilience and anonymity. In addition, we manage to realize the full T-hybrid routing prototype and test its performance in the cloud hosting environment. The experimental results show that compared with typical onion mix-nets, our T-hybrid routing mechanism only increases about 20%-25% regarding the end-to-end delay, and thus is still practical while with better resilience.</p>"

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
  caption: 'Fig.5 **Overview of the hybrid routing**'
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


